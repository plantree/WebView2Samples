## README

#### Target

A simple demo for better understanding and communicating how to use injected scripts while opening a new window.

#### File Structure

├───others --> C# side code (git clone from [GitHub](https://github.com/MicrosoftEdge/WebView2Samples/tree/main/SampleApps/WebView2WpfBrowser))
├───demo  --> JavaScript side code

#### How to use

1. Open the `.sln` in Visual Studio and run it

   ![](https://img.plantree.me/20221019171959.png)

2. Start a file server in the `Demo` directory, like listening on port 8000

3. Type `http://127.0.0.1:8000/index.html` in the address bar

   ![](https://img.plantree.me/20221019172103.png)

4. Click `Open New Window`

5. Open the DevTools

   ![](https://img.plantree.me/20221019172203.png)

6. The End