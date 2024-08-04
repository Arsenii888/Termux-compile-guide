# Termux-compile-guide
How to compile termux
<p>
If you want to compile thermex, you need the following tools in Android Studio: Android Studio ndk, sdk, java 17.
My ndk and sdk:
  </p>
<p><img src="https://github.com/user-attachments/assets/aef8cd79-500c-4b5a-a313-cc2a0288d161"/></p>
<p><img src="https://github.com/user-attachments/assets/bc6e5c10-7299-4d9c-aa37-2c30a2eb0c5e"/></p>

<p>After downloading, you need to download the termux source code.</p>
<p>You can download it from here (version 1.118.1).</p>
<p>Change it in build.gradle task download Bootstrap() { to this code</p>
<p><img src="https://github.com/user-attachments/assets/1a2b880b-acc4-467c-803f-3fce9b1169f8"/></p>
<p>Change cradle.properties as follows</p>
<p><img src="https://github.com/user-attachments/assets/91c2bbf3-8c0f-44df-813e-05d4d63175c0"/></p>
<p>And finally, move the bootstrap downloaded in advance to the cpp</p>
<p><img src="https://github.com/user-attachments/assets/3513ce62-4636-4f2a-aa44-1d537eac3291"/></p>
<p>Then you can compile it</p>
<h1>Thanks Termux for terminal emulator</h1>
<a href="https://github.com/termux">Termux
