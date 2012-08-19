# Zen-Coding Automator Services for Mac OS X #

This Automator Services script enalbes you to use Zen-Coding, powerful abbreviation features for HTML, CSS coding in Mac OS X environment.

- Requirements: [SSSCoding.pm][SSSCPM], Automator 2.2.4 or higher, Mac OS X 10.7 or higher

## Installation ##

1. Install **SSSCoding.pm**. Download from [SSSCoding.pm][SSSCPM] site. SSSCoding.pm is an Zen-Coding implementation in Perl.
2. Make sure your Perl Library Path. You can find it with a script on the terminal like `perl -e 'print $i++ . ":" . "$_\n" foreach @INC'`.
3. Copy or move SSSCoding.pm module into your Perl Library.
4. Install **ZenCoding.workflow**. Open the workflow file, then install dialogue will lauch. Or you can copy or move the workflow file into `~/Library/Services/`.


## Thanks ##

**Otchy**, author of [SSSCoding.pm][SSSCPM]. His Perl Module implementation of Zen-Coding makes me create this workflow.

**makog**, [his blog](http://d.hatena.ne.jp/makog/20110706/1309969364) shows us approches to implement zencoding features for text editor "Jedit X" with AppleScript and SSSCoding.pm. This article inspired me to develop my automator services.

## Copyright ##

Copyright 2012 luminousspice. See LICENSE for details.

[SSSCPM]: http://www.otchy.net/20100225/zen-coding-for-perl/