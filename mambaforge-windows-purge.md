<!-- wp:paragraph -->
<p>This guide will instruct on uninstalling the Anaconda Python distribution and purging the computer of old configuration files which can be problematic. The instructions can be used to uninstall Miniconda/Miniforge and Mambaforge which all leave similar configuration files behind.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Right click the Start button and select Installed Apps:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_419.png" alt="img_419"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Uninstall Anaconda, Miniconda, Mambaforge or Miniforge. Uninstall any standalone Spyder, Python and any other Python IDEs. This will clean up your computer and prevent any confusion:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_420.png" alt="img_420"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_421.png" alt="img_421"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_422.png" alt="img_422"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_423.png" alt="img_423"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Sometimes Installed Apps has an issue showing two entries for a program that has been updated. It is unable to remove the second entry once the first has been uninstalled. If this happens press ⊞ and r and input:</p>
<!-- /wp:paragraph -->

<!-- wp:kevinbatdorf/code-block-pro {"code":"appwiz.cpl","codeHTML":"\u003cpre class=\u0022shiki solarized-light\u0022 style=\u0022background-color: #FDF6E3\u0022 tabindex=\u00220\u0022\u003e\u003ccode\u003e\u003cspan class=\u0022line\u0022\u003e\u003cspan style=\u0022color: #657B83\u0022\u003eappwiz.cpl\u003c/span\u003e\u003c/span\u003e\u003c/code\u003e\u003c/pre\u003e","language":"powershell","theme":"solarized-light","bgColor":"#FDF6E3","textColor":"#657B83","fontSize":".875rem","lineHeight":"1.25rem","headerType":"headlights","seeMoreString":"","seeMoreAfterLine":"","seeMoreTransition":false,"lineHighlightColor":"rgba(43, 150, 189, 0.2)","copyButton":true} -->
<div class="wp-block-kevinbatdorf-code-block-pro" style="font-size:.875rem;line-height:1.25rem"><span style="display:block;padding:16px 0 0 16px;margin-bottom:-1px;width:100%;text-align:left;background-color:#FDF6E3"><svg xmlns="http://www.w3.org/2000/svg" width="54" height="14" viewBox="0 0 54 14"><g fill="none" fill-rule="evenodd" transform="translate(1 1)"><circle cx="6" cy="6" r="6" fill="#FF5F56" stroke="#E0443E" stroke-width=".5"></circle><circle cx="26" cy="6" r="6" fill="#FFBD2E" stroke="#DEA123" stroke-width=".5"></circle><circle cx="46" cy="6" r="6" fill="#27C93F" stroke="#1AAB29" stroke-width=".5"></circle></g></svg></span><span role="button" tabindex="0" data-code="appwiz.cpl" style="color:#657B83;display:none" aria-label="Copy" class="code-block-pro-copy-button"><svg xmlns="http://www.w3.org/2000/svg" style="width:24px;height:24px" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path class="with-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path><path class="without-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg></span><pre class="shiki solarized-light" style="background-color: #FDF6E3" tabindex="0"><code><span class="line"><span style="color: #657B83">appwiz.cpl</span></span></code></pre></div>
<!-- /wp:kevinbatdorf/code-block-pro -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_424.png" alt="img_424"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>This will launch the legacy Programs and Features which usually fares better in such a scenario:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_425.png" alt="img_425"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Open up file explorer and in the address bar input:</p>
<!-- /wp:paragraph -->

<!-- wp:kevinbatdorf/code-block-pro {"code":"%UserProfile%","codeHTML":"\u003cpre class=\u0022shiki rose-pine-dawn\u0022 style=\u0022background-color: #faf4ed\u0022 tabindex=\u00220\u0022\u003e\u003ccode\u003e\u003cspan class=\u0022line\u0022\u003e\u003cspan style=\u0022color: #286983\u0022\u003e%\u003c/span\u003e\u003cspan style=\u0022color: #575279\u0022\u003eUserProfile\u003c/span\u003e\u003cspan style=\u0022color: #286983\u0022\u003e%\u003c/span\u003e\u003c/span\u003e\u003c/code\u003e\u003c/pre\u003e","language":"powershell","theme":"rose-pine-dawn","bgColor":"#faf4ed","textColor":"#575279","fontSize":".875rem","lineHeight":"1.25rem","headerType":"headlights","seeMoreString":"","seeMoreAfterLine":"","seeMoreTransition":false,"lineHighlightColor":"rgba(49, 31, 172, 0.2)","copyButton":true} -->
<div class="wp-block-kevinbatdorf-code-block-pro" style="font-size:.875rem;line-height:1.25rem"><span style="display:block;padding:16px 0 0 16px;margin-bottom:-1px;width:100%;text-align:left;background-color:#faf4ed"><svg xmlns="http://www.w3.org/2000/svg" width="54" height="14" viewBox="0 0 54 14"><g fill="none" fill-rule="evenodd" transform="translate(1 1)"><circle cx="6" cy="6" r="6" fill="#FF5F56" stroke="#E0443E" stroke-width=".5"></circle><circle cx="26" cy="6" r="6" fill="#FFBD2E" stroke="#DEA123" stroke-width=".5"></circle><circle cx="46" cy="6" r="6" fill="#27C93F" stroke="#1AAB29" stroke-width=".5"></circle></g></svg></span><span role="button" tabindex="0" data-code="%UserProfile%" style="color:#575279;display:none" aria-label="Copy" class="code-block-pro-copy-button"><svg xmlns="http://www.w3.org/2000/svg" style="width:24px;height:24px" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path class="with-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path><path class="without-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg></span><pre class="shiki rose-pine-dawn" style="background-color: #faf4ed" tabindex="0"><code><span class="line"><span style="color: #286983">%</span><span style="color: #575279">UserProfile</span><span style="color: #286983">%</span></span></code></pre></div>
<!-- /wp:kevinbatdorf/code-block-pro -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_426.png" alt="img_426"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Delete the old configuration folders:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><!-- wp:list-item -->
<li> .conda</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>.continuum</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>.ipython</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>.jupyter</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>.matplotlib</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>.spyder-py3</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_427.png" alt="img_427"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Delete the folder:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><!-- wp:list-item -->
<li>jedi</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_428.png" alt="img_428"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Delete the file:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><!-- wp:list-item -->
<li>.condarc</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>Having an old version of this file from a previous Anaconda installation and then installing Mambaforge for example without deleting this file may result in the mamba package manager using the wrong channel (conda instead of conda-forge) which can be problematic:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_429.png" alt="img_429"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Open up file explorer and in the address bar input:</p>
<!-- /wp:paragraph -->

<!-- wp:kevinbatdorf/code-block-pro {"code":"%AppData%","codeHTML":"\u003cpre class=\u0022shiki rose-pine-dawn\u0022 style=\u0022background-color: #faf4ed\u0022 tabindex=\u00220\u0022\u003e\u003ccode\u003e\u003cspan class=\u0022line\u0022\u003e\u003cspan style=\u0022color: #286983\u0022\u003e%\u003c/span\u003e\u003cspan style=\u0022color: #575279\u0022\u003eAppData\u003c/span\u003e\u003cspan style=\u0022color: #286983\u0022\u003e%\u003c/span\u003e\u003c/span\u003e\u003c/code\u003e\u003c/pre\u003e","language":"powershell","theme":"rose-pine-dawn","bgColor":"#faf4ed","textColor":"#575279","fontSize":".875rem","lineHeight":"1.25rem","headerType":"headlights","seeMoreString":"","seeMoreAfterLine":"","seeMoreTransition":false,"lineHighlightColor":"rgba(49, 31, 172, 0.2)","copyButton":true} -->
<div class="wp-block-kevinbatdorf-code-block-pro" style="font-size:.875rem;line-height:1.25rem"><span style="display:block;padding:16px 0 0 16px;margin-bottom:-1px;width:100%;text-align:left;background-color:#faf4ed"><svg xmlns="http://www.w3.org/2000/svg" width="54" height="14" viewBox="0 0 54 14"><g fill="none" fill-rule="evenodd" transform="translate(1 1)"><circle cx="6" cy="6" r="6" fill="#FF5F56" stroke="#E0443E" stroke-width=".5"></circle><circle cx="26" cy="6" r="6" fill="#FFBD2E" stroke="#DEA123" stroke-width=".5"></circle><circle cx="46" cy="6" r="6" fill="#27C93F" stroke="#1AAB29" stroke-width=".5"></circle></g></svg></span><span role="button" tabindex="0" data-code="%AppData%" style="color:#575279;display:none" aria-label="Copy" class="code-block-pro-copy-button"><svg xmlns="http://www.w3.org/2000/svg" style="width:24px;height:24px" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path class="with-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path><path class="without-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg></span><pre class="shiki rose-pine-dawn" style="background-color: #faf4ed" tabindex="0"><code><span class="line"><span style="color: #286983">%</span><span style="color: #575279">AppData</span><span style="color: #286983">%</span></span></code></pre></div>
<!-- /wp:kevinbatdorf/code-block-pro -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_430.png" alt="img_430"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Delete the folders:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><!-- wp:list-item -->
<li> .anaconda</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>jupyter</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_431.png" alt="img_431"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Press alt and ↑ to go up a level and then select the Roaming subfolder:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_432.png" alt="img_432"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Delete the folders:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><!-- wp:list-item -->
<li>conda</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>seaborn</li>
<!-- /wp:list-item -->

<!-- wp:list-item -->
<li>spyder</li>
<!-- /wp:list-item --></ul>
<!-- /wp:list -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_433.png" alt="img_433"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_434.png" alt="img_434"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Go to the Microsoft folder, select Windows, Start Menu and Programs and delete any old Start Menu entries:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_442.png" alt="img_442"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_443.png" alt="img_443"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_444.png" alt="img_444"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_445.png" alt="img_445"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_446.png" alt="img_446"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Open up file explorer and in the address bar input:</p>
<!-- /wp:paragraph -->

<!-- wp:kevinbatdorf/code-block-pro {"code":" %ProgramData%","codeHTML":"\u003cpre class=\u0022shiki solarized-light\u0022 style=\u0022background-color: #FDF6E3\u0022 tabindex=\u00220\u0022\u003e\u003ccode\u003e\u003cspan class=\u0022line\u0022\u003e\u003cspan style=\u0022color: #657B83\u0022\u003e \u003c/span\u003e\u003cspan style=\u0022color: #859900\u0022\u003e%\u003c/span\u003e\u003cspan style=\u0022color: #657B83\u0022\u003eProgramData\u003c/span\u003e\u003cspan style=\u0022color: #859900\u0022\u003e%\u003c/span\u003e\u003c/span\u003e\u003c/code\u003e\u003c/pre\u003e","language":"powershell","theme":"solarized-light","bgColor":"#FDF6E3","textColor":"#657B83","fontSize":".875rem","lineHeight":"1.25rem","headerType":"headlights","seeMoreString":"","seeMoreAfterLine":"","seeMoreTransition":false,"lineHighlightColor":"rgba(43, 150, 189, 0.2)","copyButton":true} -->
<div class="wp-block-kevinbatdorf-code-block-pro" style="font-size:.875rem;line-height:1.25rem"><span style="display:block;padding:16px 0 0 16px;margin-bottom:-1px;width:100%;text-align:left;background-color:#FDF6E3"><svg xmlns="http://www.w3.org/2000/svg" width="54" height="14" viewBox="0 0 54 14"><g fill="none" fill-rule="evenodd" transform="translate(1 1)"><circle cx="6" cy="6" r="6" fill="#FF5F56" stroke="#E0443E" stroke-width=".5"></circle><circle cx="26" cy="6" r="6" fill="#FFBD2E" stroke="#DEA123" stroke-width=".5"></circle><circle cx="46" cy="6" r="6" fill="#27C93F" stroke="#1AAB29" stroke-width=".5"></circle></g></svg></span><span role="button" tabindex="0" data-code=" %ProgramData%" style="color:#657B83;display:none" aria-label="Copy" class="code-block-pro-copy-button"><svg xmlns="http://www.w3.org/2000/svg" style="width:24px;height:24px" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path class="with-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path><path class="without-check" stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg></span><pre class="shiki solarized-light" style="background-color: #FDF6E3" tabindex="0"><code><span class="line"><span style="color: #657B83"> </span><span style="color: #859900">%</span><span style="color: #657B83">ProgramData</span><span style="color: #859900">%</span></span></code></pre></div>
<!-- /wp:kevinbatdorf/code-block-pro -->

<!-- wp:paragraph -->
<p>This location is used if one of these programs is installed for All Users. Look for the analogous folders to those seen in the User Profile above and delete them:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_435.png" alt="img_435"/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_436.png" alt="img_436"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Right click the Start Button and select System:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_447.png" alt="img_447"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Select Advanced System Settings:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_448.png" alt="img_448"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Select Environmental Variables:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_449.png" alt="img_449"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Select the Path and select Edit:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_450.png" alt="img_450"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Ensure there are no old entries to Anaconda, Miniconda, Mambaforge, Miniforge or Python:</p>
<!-- /wp:paragraph -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://raw.githubusercontent.com/PhilipYip1988/python-tutorials/main/001_install/001_windows_install/images/img_451.png" alt="img_451"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>This gives a clean Windows Operating System to install Mambaforge or an updated version of Anaconda.</p>
<!-- /wp:paragraph -->
