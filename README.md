## I got tired of this:

    psql:lib/sql/similarity.sql:97: ERROR:  column o.user_id does not exist at character 426
    
## So now I do this:

    find_psql_error "psql:lib/sql/similarity.sql:97: ERROR:  column o.user_id does not exist at character 426"
    
## And I get this:

![screen shot](http://github.com/jaylevitt/find_psql_error/raw/master/screen-shot.png)