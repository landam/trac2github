Features:
- Converts milestones/tickets/comments/labels
- Converts Trac usernames to Github usernames
- Sets assignees if possible, sets you an assignee otherwise
- Supports manual splitting of conversion process into stages
- Slows down to match the 60 requests per second API limit rate

Usage:
1. Copy the configuration file template, `trac2github.cfg_template` to `trac2github.cfg`
2. Edit the configuration variables in the configuration file `trac2github.cfg`
3. Run the PHP script `trac2github.php` from a shell prompt, e.g.:  
    `$ php trac2github.php`

Known Problems:
- Strips some characters from ticket bodys / comments like ü/ä/ö etc.

