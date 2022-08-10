# unimplemented
NotImplementedException for PHP.

> Inspired by .NET's `NotImplementedException`[^1].

This package exposes a single `NotImplementedException` class, and nothing else.

`NotImplementedException` extends the [SPL](https://www.php.net/manual/en/book.spl.php)'s `BadMethodCallException`[^2].

## Usage

Usage should be quite straightforward.

```php
<?php

use Shuleni\Unimplemented\NotImplementedException;

function SolveWorldHunger(Universe\Models\Planet $input): Universe\Models\Solution {
  throw new NotImplementedException();
}
```

[^1]: https://docs.microsoft.com/en-us/dotnet/api/system.notimplementedexception
[^2]: https://www.php.net/manual/en/class.badmethodcallexception.php
