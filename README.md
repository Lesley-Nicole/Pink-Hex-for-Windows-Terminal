# **Pink Hex**

![Pink Hex!](assets/pinkHexLogo.jpg)

**A pink, semi-transparent theme for Windows Terminal.**

---

![Pink Hex for Windows Terminal!](/assets/pinkHex.png)

## **Prerequisites**

- Windows Terminal(windows store)

- Text editor

### **Download**

Download using the [Github.zip download](https:://
github.com/pink-hex-for-windows-terminal/master.zip)
option.

#### **Install**

- Start Windows Terminal and click on the down arrow symbol from the menu bar. Then select Settings option from the dropdown menu.

- In the settings.json file for Windows Terminal, paste the content of pinkhex.json into the **schemes** section.

**Like this:**

    "schemes": [
        {
            "name": "Pink Hex",
            "background": "#F532F5",
            "cursorColor": "#FF089D",
            "foreground": "#FFFFFF"
        }
    ]

Now that you have the scheme set, choose which terminal profile, or profiles, you want to use it on, then paste the following pinkhex.json content.

**Example:**

    "profiles": {
      "defaults": {},
        "list": [
       {
          "useAcrylic": true,
          "acrylicOpacity": 0.2,
          "guid":"(61x54xxx-x2x6-5271-96x7-009x87xx44xx)"
          "colorScheme": "Pink Hex",
          "hidden": false,
          "name": "Ubuntu",
          "source": "Windows.Terminal.Wsl",
          "tabColor": "#ff00bf",
          "padding": "8, 8, 8, 8",
          "backgroundImage": "/assets/pinkHex.png",
          "backgroundImageOpacity": 0.5,
          "backgroundImageAlignment": "cente
          "backgroundImageStretchMode": "uni
        }
    ]

##### **If everything is set correctly, your terminal should look something like this:**

![Screenshot!](/assets/pinkHexScreen.jpg)

---

Made by ![Lesley-Nicole!](/assets/logo_lesley.png)

###### MIT License
