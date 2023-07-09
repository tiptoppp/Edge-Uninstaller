## Edge Uninstaller

    @echo off
    title Edge Uninstaller
    takeown /F "C:\Program Files (x86)\Microsoft" /A /R
    rmdir /s /Q "C:\Program Files (x86)\Microsoft\Edge"
    rmdir /s /Q "C:\Program Files (x86)\Microsoft\EdgeCore"
    rmdir /s /Q "C:\Program Files (x86)\Microsoft\EdgeUpdate"
    rmdir /s /Q "C:\Program Files (x86)\Microsoft\EdgeWebView"
    rmdir /s /Q "C:\Program Files (x86)\Microsoft\Temp"
