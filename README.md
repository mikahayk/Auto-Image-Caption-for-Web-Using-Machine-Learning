# Auto Image Caption for Web
<h3> A Chrome Extension that uses machine learning to auto caption images and fix missing Alt Texts</h3>

![a11y-extension-cover](https://user-images.githubusercontent.com/3223085/106404186-fac5a800-63ff-11eb-9001-813541efa62f.jpg)

<h4>DESCRIPTION</h4>
Digital accessibility ensures that websites, web apps, and digital content can be used by people with a diverse range of hearing, movement, sight or cognitive abilities.
One way to promote digital accessibility is by using alt text (alternative text), which provides a text alternative to non-text content in web pages including images, media, etc.
Alt text can be challenging to audit, edit and/or update in existing websites. This Chrome extension will automate this process by using machine learning and image detection. IM2TXT captioning is the model used in this project.

<h4>IM2TXT Model</h4>
The image encoder is a deep convolutional neural network. This type of network is widely used for image tasks and is currently state-of-the-art for object recognition and detection. Our particular choice of network is the Inception v3 image recognition model pretrained on the ILSVRC-2012-CLS image classification dataset. The decoder is a long short-term memory (LSTM) network. This type of network is commonly used for sequence modeling tasks such as language modeling and machine translation. In the Show and Tell model, the LSTM network is trained as a language model conditioned on the image encoding.

<h4>INSPIRATION</h4>
<ul>
  <li><a href="https://www.youtube.com/watch?v=kS53y6GWm0w" target="_blank">Making Amazon Alexa respond to Sign Language using AI</a></li>
  <li><a href="https://chrome.google.com/webstore/category/ext/22-accessibility?hl=en" target="_blank">Accessibility Extensions</a></li>
<li>Abi and I audited ITP websites to check if they were compliant with NYU Accessibility standards our first semester at ITP</li>
</ul>

<h4>REFERENCES</h4>
<ul>
<li><a target="_blank" href="https://chrome.google.com/webstore/detail/auto-alt-text/lgmkhmedpaidhgonghfhijjlgaballje?hl=en">Auto Alt Text</a> - Need to click on the image before alt text appears</li>
<li><a target="_blank" href="https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh?hl=en-US">Wave Evaluation Tool</a> - Evaluate web accessibility within the Chrome browser</li>
<li><a target="_blank" href="https://cloudinary.com/blog/making_media_accessible_how_to_automatically_generate_alt_text_for_images">Cloudinary Add-ons</a> - Cloudinary takes care of your entire image management pipeline. With Cloudinary Add-ons, you can enhance your images even further with powerful functionality</li>
<li><a target="_blank" href="http://assets20.sigaccess.org/">ACM SIGACCESS Conference on Computers and Accessibility</a></li>
<li><a target="_blank" href="https://dl.acm.org/citation.cfm?id=2998364">Automatic Alt-text: Computer-generated Image Descriptions for Blind Users on a Social Network Service </a>- Designed and deployed automatic alt-text (AAT), a system that applies computer vision technology to identify faces, objects, and themes from photos to generate photo alt-text for screen reader users on Facebook</li>
<li><a target="_blank" href="https://twitter.com/CatchTheseWords/status/1195742305761644544">Emojis and screenreaders - &ldquo;This is social media when you are blind.&rdquo;</a></li>
</ul>

<h4>AUDIENCE</h4>
<ul>
  <li>People who utilize a screenreader to access alt text</li>
  <li>People who need update alt text retroactively to comply with digital accessibility standards</li>
</ul>

<h4>NEXT STEPS</h4>
<ul>
  <li>Make it a WP plugin</li>
  <li>Generate images based on labels</li>
  <li>Use ML to provide a better screen reader experience</li>
  <li>Retain model on web semantics</li>
</ul>

<h4>INSTRUCTIONS</h4>
<ol>
  <li>Download this repo.</li>
  <li>Archive it into a .zip file. </li>
  <li>Go to chrome://extensions/ and enable the extension.</li>
  <li>Open any webpage.</li>
  <li>Run the extension.</li>
 </ol>
 
by Hayk Mikayelyan, Abi Muñoz. <br/>
<sub>Thank you Yining Shi, Lauren Race, Ellen Nickels for helping us with this project. </sub>
