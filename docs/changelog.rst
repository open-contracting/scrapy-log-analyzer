Changelog
=========

Unreleased
----------

Changed
~~~~~~~

-  Add support for Python 3.13.
-  Drop support for Python 3.9.

0.0.5 (2025-02-20)
------------------

Changed
~~~~~~~

Kingfisher Collect writes ERROR-level messages instead of yielding FileError items.

0.0.4 (2025-02-07)
------------------

Fixed
~~~~~

-  :meth:`scrapyloganalyzer.ScrapyLogFile.error_rate`: Fix division by zero error for all cases.

0.0.3 (2025-01-30)
------------------

Fixed
~~~~~

-  :meth:`scrapyloganalyzer.ScrapyLogFile.error_rate`: Fix division by zero error if only file items are yielded.

0.0.2 (2025-01-29)
------------------

Added
~~~~~

-  :meth:`scrapyloganalyzer.ScrapyLogFile.read` returns the text content of the log file.
-  :meth:`scrapyloganalyzer.ScrapyLogFile.__iter__` yields each line of the log file.

Changed
~~~~~~~

-  :meth:`scrapyloganalyzer.ScrapyLogFile.__init__` accepts a ``text`` keyword argument.

0.0.1 (2024-12-13)
------------------

First release.
