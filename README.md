## Debug traffic between Android, iOS and anyone mAPI


Define user interface by template:
- **method**

    - `parameter` [`type` | `short explanation`] - description 


- **run**:
    
    - *request* [`bool`] - receive outgoing calls API from the device
    - *response* [`bool`] - accept incoming replies from the device
    - *mapi_handler* [`func`]- handler for writing to the mapi.log by template `mapi.kassa.rambler.ru`
    - *other_handler* - handler for writing to the other.log
    - *file_logging* - 