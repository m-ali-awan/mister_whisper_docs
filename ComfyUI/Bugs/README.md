

<details>
<summary>No module named "comfy.options"</summary>

- Issue is caused by installation of following package, which is most probably installed while installing some custom extension:
    ![screenshot of problematic package](image.png)
- So we have to unistall this and pip package of comfy, so it can make use of comfy folder under **ComfyUI**
    - For this, as we don't have terminal in StabilityMatrix, we have to first go in the venv and then do this uninstalling:
        1. Open Terminal with Administrator Access
        2. cd into location `C:\Users\17148\AppData\Roaming\StabilityMatrix\Packages\ComfyUI`
        3. Activate ven by following command:
            `venv\Scripts\activate`
        4. And then type:
            `pip3 uninstall comfy`
    > Now, Launch ComfyUI from Stabilty Matrix, and it will work