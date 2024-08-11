## Description

The web application allows users to enter a domain or IP address and click a button to ping that address. The application then measures the round-trip time it takes to ping the specified address and displays the result.

## Setup

1. **Download the HTML File**:
   - Save the provided [HTML code](ping_test.html) to a file named `ping_test.html`.

2. **Open the HTML File**:
   - Simply open the `ping_test.html` file in any modern web browser (e.g., Chrome, Firefox, Edge).

## Usage

1. **Enter the Domain or IP Address**:
   - Type the domain name (e.g., `google.com`) or IP address you want to ping into the input box.

2. **Click the "Ping" Button**:
   - After entering the address, click the "Ping" button to start the ping test.

3. **View the Result**:
   - The ping time will be displayed below the input box in milliseconds. If the ping fails, an error message will be shown.

## Example

1. **Enter**: Enter `google.com` in the input field.
2. **Ping**: Click the "Ping" button.
3. **Result**: The page will display something like:
```sh
Ping to google.com was successful. Time: 40 ms
```

>[!NOTE]
> - The ping test uses the `fetch` API to send a request to the specified domain. Since this is done client-side, it won't work with local IP addresses or if there are CORS restrictions on the server.
> - This tool is best used to measure the time it takes to establish a connection to a public server or website.
> - This HTML page with embedded JavaScript code will allow you to perform a basic ping test to a domain or IP address. Note that this is a simple client-side implementation and may have limitations compared to traditional ping utilities.

>[!IMPORTANT]
> - Feel free to modify the code to better fit your specific needs or to add more detailed ping functionality.✍️
> - This project is protected under the [MIT License](LICENSE). :shipit:
