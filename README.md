<h2>Overview</h2>
<p>QR Mate is a versatile and user-friendly application designed for generating, scanning, and managing QR codes. Built using Kotlin, the app leverages modern tools and frameworks to provide a seamless user experience. It offers robust features such as saving QR codes locally, sharing functionality, and offline deletion management with Firebase integration.</p>

<hr>

<h2>Features</h2>
<ul>
    <li><strong>QR Code Generation</strong>
        <ul>
            <li>Generate QR codes from text, URLs, or custom input.</li>
        </ul>
    </li>
    <li><strong>QR Code Scanning</strong>
        <ul>
            <li>Scan QR codes using the device camera or select an image containing a QR code from the gallery.</li>
        </ul>
    </li>
    <li><strong>Save and Manage QR Codes</strong>
        <ul>
            <li>Save generated QR codes to local storage.</li>
            <li>Integrated with Firebase for cloud storage.</li>
        </ul>
    </li>
    <li><strong>Sharing Options</strong>
        <ul>
            <li>Share QR codes directly via supported sharing options.</li>
        </ul>
    </li>
    <li><strong>Offline Deletion Management</strong>
        <ul>
            <li>Uses Room Database to queue deletions when offline.</li>
            <li>Automatically syncs deletions with Firebase when back online.</li>
        </ul>
    </li>
    <li><strong>Modern UI</strong>
        <ul>
            <li>Intuitive user interface with support for both light and dark themes.</li>
        </ul>
    </li>
</ul>

<hr>

<h2>Technology Stack</h2>
<ul>
    <li><strong>Language:</strong> Kotlin</li>
    <li><strong>Architecture:</strong> MVVM</li>
    <li><strong>Database:</strong> Room Database, Firebase Realtime Database</li>
    <li><strong>UI Frameworks:</strong> Material Design Components</li>
    <li><strong>Other Libraries:</strong>
        <ul>
            <li>Picasso/Glide: For image loading</li>
            <li>Retrofit: For network operations</li>
        </ul>
    </li>
</ul>

<hr>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
    <li>Android Studio</li>
    <li>A device or emulator running Android 6.0 (Marshmallow) or higher</li>
    <li>Firebase project setup with Realtime Database</li>
</ul>

<h3>Download and Installation</h3>
<ol>
    <li>Download the latest release APK from the <a href="https://github.com/gourav-jamdhade/QR-Mate/releases/download/app/QR.Code.Generator.and.Manager.App.apk">Releases</a> section.</li>
    <li>Transfer the APK to your Android device.</li>
    <li>Enable installation from unknown sources if prompted.</li>
    <li>Install the APK by opening it on your device.</li>
</ol>
<hr>

<h2>Usage</h2>
<ol>
    <li><strong>Home Screen</strong>:
        <ul>
            <li>Choose between generating or scanning a QR code.</li>
        </ul>
    </li>
    <li><strong>Generate QR Code</strong>:
        <ul>
            <li>Enter text or a URL and tap "Generate".</li>
        </ul>
    </li>
    <li><strong>Scan QR Code</strong>:
        <ul>
            <li>Use the camera to scan or upload an image from the gallery.</li>
        </ul>
    </li>
    <li><strong>Manage QR Codes</strong>:
        <ul>
            <li>View saved QR codes, delete them, or share them as needed.</li>
        </ul>
    </li>
    <li><strong>Settings</strong>:
        <ul>
            <li>Configure preferences, including theme options.</li>
        </ul>
    </li>
</ol>

<hr>

<h2>Contribution</h2>
<ol>
    <li>Fork the repository.</li>
    <li>Create a feature branch:
        <pre><code>git checkout -b feature-name</code></pre>
    </li>
    <li>Commit your changes:
        <pre><code>git commit -m "Add some feature"</code></pre>
    </li>
    <li>Push to the branch:
        <pre><code>git push origin feature-name</code></pre>
    </li>
    <li>Open a pull request.</li>
</ol>

<hr>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

<hr>

<h2>Contact</h2>
<p><strong>Developer:</strong> Gourav Jamdhade</p>
<p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/gouravjamdhade">linkedin.com/in/gouravjamdhade</a></p>
<p><strong>GitHub:</strong> <a href="https://github.com/gourav-jamdhade">github.com/gourav-jamdhade</a></p>

<hr>

<p>Thank you for using QR Mate!</p>
