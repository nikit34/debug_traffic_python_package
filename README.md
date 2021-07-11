## Debug traffic between Android, iOS and anyone mAPI


Define user interface by template:
- **method** / **field** (`field` if this defined) **

    ```
    General description
    ```

    - *parameter* [`type` | `short explanation`] - description 


- **run**: 

    ```
    Launching interceptor threads in asynchronous execution and logging, setting the debugger operating mode
    ```
    
    - *request* [`bool`] - receive outgoing calls API from the device
    - *response* [`bool`] - accept incoming replies from the device
    - *mapi_handler* [`func`] - handler for filtering defined inside and by template `mapi.kassa.rambler.ru`
    - *other_handler* [`func`] - handler for filtering defined inside
    - *file_logging* [`bool`] - enable/disable file logging separated on two local files: `other.log` and `mapi.log` by template `mapi.kassa.rambler.ru`
    - *switch_proxy* [`bool`] - enable/disable proxy mode between the simulator and the server through the system settings of the mac os
    - *timeout_recard* [`int`] - delayed execution of the start of logging in seconds

- **kill**:

    ```
    Stopping threads and cleaning log files
    ```

- **dbg_api.t.open_loop** (field)

    - value is *False* if need to terminate the work of asynchronous interception of requests (default *True*)

- **read_buffer**
    