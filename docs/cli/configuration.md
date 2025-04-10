# Configuration

* allows
  * 👀enable ALWAYS SOME flags on 👀
* == -- via -- environment variables /
  * `CONCURRENTLY_` == prefix 
  * _Example:_
    ```bash
    $ export CONCURRENTLY_KILL_OTHERS=true
    $ export CONCURRENTLY_HANDLE_INPUT=true
    
    $ concurrently nodemon "echo 'hey nodemon, you won't last long'"
    # ==  $ concurrently --kill-others --handle-input nodemon "echo 'hey nodemon, you won't last long'"
    ```
