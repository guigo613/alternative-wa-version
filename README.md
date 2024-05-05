# Alternative wa-version
[![Sponsor](https://img.shields.io/badge/Sponsor-Donate-green.svg)](https://github.com/sponsors/guigo613)

This repository contains an alternative version of WhatsApp, focused on fixing the issue of videos not being sent correctly to the API.

## Features

- Fixes the issue of videos not being sent to the WhatsApp API.
- Maintains basic functionality of text messaging and media sharing.

## How to Use

1. Copy the file found in this repository (likely a file fixing the video sending issue) to the correct location within the `whatsapp-web.js` project, according to their API structure. This may involve replacing or adding files in the appropriate directories of the `whatsapp-web.js` project.

2. In your code, when creating an instance of WhatsApp Web JS API, pass the `webVersion: "2.2412.54v2"` parameter in the constructor:

    ```javascript
    const { Client } = require('whatsapp-web.js');
    
    const client = new Client({
        webVersion: "2.2412.54v2"
    });
    ```

    Ensure to replace `"2.2412.54v2"` with the specific version you need to use. For more information, refer to the [WhatsApp Web JS API](https://github.com/pedroslopez/whatsapp-web.js).

3. Utilize the WhatsApp Web JS API as needed in your project, leveraging the fix or enhancement provided by the file added to the `whatsapp-web.js` project.
1. 
## Contributing

Feel free to contribute to this project! If you encounter any issues or have an idea for a new feature, please open an issue or submit a pull request.

## Contact

For more information, contact Guilherme via guigo613@gmai.com.

