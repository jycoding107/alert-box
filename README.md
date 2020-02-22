<h2>Video Demo</h2>
<a href="https://youtu.be/nRakOCusuTk" target="_blank">https://youtu.be/nRakOCusuTk</a>
<h2>Overview</h2>
<p>
  There are total of 3 main types of alert box or modal popup being developed:
  <ol>
    <li>Bootstrap Alert Box with Close Button on the Right</li>
    <li>Bootstrap Alert Box which will auto close after 1.5 seconds</li>
    <li>Bootstrap Modal Popup (Light Theme and Dark Theme)</li>
</ol>
</p>
<h2>Screenshots</h2>
<img src="https://padlet-uploads.storage.googleapis.com/432143275/2b3d36cc5a69e857e7d60c894e1489e4/image.png" alt="withCloseBtn" />
<img src="https://padlet-uploads.storage.googleapis.com/432143275/e6c09d6c0ece82134bdca00429ac7c53/image.png" alt="autoclose" />
<img src="https://padlet-uploads.storage.googleapis.com/432143275/2189990a6713a1079157e07b5387d43e/image.png" alt="light" />
<img src="https://padlet-uploads.storage.googleapis.com/432143275/1e9b587e28549dbd31dcc9416ac49504/image.png" alt="dark" />
<h2>Code Layout</h2>
<ul>
  <li>All the alerts / modal popup are a partial view in /Views/Shared folder.</li>
  <li>They can be added in main view easily by @Html.Partial("AlertFileName").</li>
  <li>For showing & hiding the alert, they are manipulated in script part in "/Views/Home/Index.cshtml"</li>
  <li>For styling of the modal popup's background color and foreground color, they are manipulated in style part in "/Views/Home/Index.cshtml"</li>
  </ul>
