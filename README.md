
### Installation
To install the necessary dependencies, run the following command:

npm i


### Execution Instructions
To use the scripts, execute the appropriate command in your terminal as per your requirement:

- For `CyberRapidHTTP2.js`, use:
node CyberRapidHTTP2.js ```<url> <time> <rps> <threads> <proxies>```


- For `CyberBypassHTTP2.js`, use:


node CyberBypassHTTP2.js ```<url> <time> <rps> <type> <threads> <proxies>```


#### Parameters:
- `<url>`: The target URL.
- `<time>`: Duration of the attack in seconds.
- `<rps>`: Requests per second.
- `<type>`: Attack type (Applicable for CyberBypassHTTP2.js only).
- `<threads>`: Number of threads.
- `<proxies>`: Proxy list.

#### Attack Types for CyberBypassHTTP2.js:
- `0`: Get Methods
- `2`: Get, Spoof
- `3`  Post
- `4`  Mix
