# Tunneling With Ngrok

**To set up tunneling with ngrok, follow these steps:**

1. **Create an ngrok account:** Sign up for an account on the [ngrok website](https://ngrok.com/).

2. **Generate an auth token:** Once you have an account, create an auth token in the auth token menu.

3. **Install ngrok on your server:** Install ngrok on your server using the appropriate command for your operating system:

   * **For Debian/Ubuntu:**

     ```bash
     sudo apt install ngrok
     ```

   * **For other Linux distributions:**

     ```bash
     sudo snap install ngrok
     ```

4. **Authenticate ngrok:** Connect the server to your ngrok account by authenticating it with your auth token using the following command:

   ```bash
   ngrok config add-authtoken your-auth-token
   ```

   Replace `your-auth-token` with the actual auth token you generated in step 2.

5. **Start tunneling:** Once ngrok is authenticated, you can start tunneling a web service running on port 80 using the following command:

   ```bash
   ngrok http 80
   ```

   This will create a secure tunnel that exposes your local web service to the public internet. You can access your web service using the URL displayed in the ngrok output.
