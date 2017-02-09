csv-import-example
==================

An example of importing a CSV into two entities, one related to the other, using
a Symfony 3 console command and League CSV.

``` language-bash
➜  csv-import-example php bin/console doctrine:schema:update --force
Updating database schema...
Database schema updated successfully! "3" queries were executed

➜  csv-import-example php bin/console csv:import                      

Attempting import of Feed...
============================

 1000/1000 [▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] 100%

                                                                                                                        
 [OK] Command exited cleanly!                                                                                           
                                                                                                                        

```