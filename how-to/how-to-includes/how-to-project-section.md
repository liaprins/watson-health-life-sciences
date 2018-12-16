<li>
	Visit your project page to determine if it already has additional sections beyond the default "Team members" section. If there are more section(s) listed in the page's left sidebar beyond just "Team members", you can skip ahead to <strong>step 18</strong>. Otherwise, if there are no additional sections, go to <strong>step 2</strong>.
	<ul>
		<li>
			The sidebar or menu features a list of links to all sections of a page and is located on the left side of the page, below the page title.
		</li>
	</ul>
</li>
<li>
	Go to the <a href="https://github.ibm.com{{ site.baseurl }}/tree/gh-pages" target="_blank">Github project for your market page</a>. Go into the <strong>projects</strong> folder and open the <strong>index.md</strong> file.
</li>
<li>
	Around <strong>line 20</strong> should be a line of code that contains this phrase: <br />
	<span class="code">REPLACE_WITH_YOUR_PROJECT_FOLDER_NAME_LOWERCASE</span>. <br />
	Maintain the straight single-quotes surrounding it (<span class="code">' '</span>) and add the name you gave to your project folder in <strong>step 2</strong>, character-for-character, all lowercase.
	<ul>
		<li>
			Make sure there are no spaces between the straight quotes and the project folder name you enter.
		</li>
	</ul>
</li>
<li>
	Click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	Go back out to <strong>your project</strong> folder, and then into the <strong>project-includes</strong> folder. Open the <strong>project-menu.md</strong> file.
	<ul>
		<li>
			You can get to <strong>your project</strong> folder by clicking the blue link to it in the breadcrumb at the top left.
		</li>
	</ul>
</li>
<li>
	Around <strong>line 5</strong> should be a line of code that contains the same phrase: <br />
	<span class="code">REPLACE_WITH_YOUR_PROJECT_FOLDER_NAME_LOWERCASE</span>. <br />
	Repeat what you just did in the index file: maintain the straight single-quotes surrounding the phrase (<span class="code">' '</span>) and add the name you gave to your project folder in <strong>step 2</strong>, character-for-character, all lowercase.
	<ul>
		<li>
			Make sure there are no spaces between the straight quotes and the project folder name you enter.
		</li>
	</ul>
</li>
<li>
	Click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	Download the folder and file template for an additional section from <a href="https://ibm.box.com/v/first-project-section-template" target="_blank">Box</a> and unzip the compressed folder.
</li>
<li>
	Open the <strong>project-sections</strong> folder and rename the file inside appropriately to describe the first section you want to add, maintaining the <strong>.md</strong> extension.
	<ul>
		<li>
			Keep the name as short as you can, like "project-onboarding.md".
		</li>
		<li>
			Make sure everything is lowercase. Avoid any spaces (use underscores or hyphens instead). Avoid special characters like "!" or "@".
		</li>
		<li>
			Do <em>not</em> change the name of the folder it is in!
		</li>
	</ul>
</li>
<li>
	Navigate into your project folder. Click <strong>Upload files</strong> in the top right. Then drag-and-drop the freshly downloaded <strong>project-sections</strong> folder as a whole. Once it's finished loading, click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	After a couple seconds of processing the files, Github will kick you back out to your market's main page of code. Navigate back into the <strong>projects</strong> folder, then into your <strong>specific project folder</strong> and from there into the newly added <strong>project-sections</strong> folder.
</li>
<li>
	Inside you should find the file you had re-named. Open it and click the pencil icon in the top right to edit.
</li>
<li>
	Supply content for each of the prompts listed between the <span class="code">---</span> borders on top and bottom, as described below. Maintain a space between the colon and your response.
	<ul>
		<li>
			<strong>section: </strong>Provide the full name for your section. It will appear as a link in the left sidebar of your project page.
		</li>
		<li>
			<strong>anchorlink: </strong>Provide one word that sums up the section. This won't appear in the content but it will be used behind-the-scenes in the code to link the section name in the sidebar to the part of the project page where this section content appears. If I named my section "How to grow a cactus" I might give it the anchorlink "cactus".
		</li>
	</ul>
</li>
<li>
	In the first line of text below the lower <span class="code">---</span> border, you'll see the phrase: <br />
	<span class="code">REPEAT_THE_CONTENT_YOU_SUPPLIED_FOR_THE_section_<br />
	VARIABLE_ABOVE_HERE</span>.<br />
	As it suggests, replace the phrase with the full name you supplied for the <span class="code">section:</span> prompt in the previous step.
	<ul>
		<li>
			Simply double-click the phrase to highlight it all, then paste in the content you supplied for the <span class="code">section:</span> prompt.
		</li>
		<li>
			Leave the hashtags (<span class="code">##</span>) and other surrounding text alone.
		</li>
	</ul>
</li>
<li>
	In the same line of text, you'll see the phrase: <br />
	<span class="code">REPEAT_THE_CONTENT_YOU_SUPPLIED_FOR_THE_<br />
	anchorlink_VARIABLE_ABOVE_HERE</span>.<br />
	As it suggests, replace the phrase with the word you supplied for the <span class="code">anchorlink:</span> prompt.
	<ul>
		<li>
			Again, simply double-click the phrase to highlight it all, then paste in the content you supplied for the <span class="code">anchorlink:</span> prompt.
		</li>
		<li>
			Leave the hashtag (<span class="code">#</span>) and the surrounding curly braces <span class="code">{ }</span>) alone. Make sure there's no space between your typed anchorlink and the hashtag (<span class="code">#</span>), and no space between it and the closing curly brace hashtag (<span class="code">}</span>).
		</li>
	</ul>
</li>
<li>
	Below, replace <span class="code">[ADD CONTENT FOR THE SECTION HERE]</span> with the content you want the section to hold.
	<ul>
		<li>
			If you leave your entry as plain text, it will appear as a regular paragraph on your project page. You can add styling and formatting to your section if you want, too. Follow the steps to <strong><a href="style">Style a page section</a></strong> below for guidance. 
		</li>
	</ul>
</li>
<li>
	Click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	If you want to add another section to your project page, you can download the template for a single section from <a href="https://ibm.box.com/v/new-project-section-template" target="_blank">Box</a>.
</li>
<li>
	Rename the file appropriately to describe the section you want to add, maintaining the <strong>.md</strong> extension.
	<ul>
		<li>
			Keep the name as short as you can, like "project-principles.md".
		</li>
		<li>
			Make sure everything is lowercase. Avoid any spaces (use underscores or hyphens instead). Avoid special characters like "!" or "@".
		</li>
	</ul>
</li>
<li>
	Navigate into <strong>your project</strong> folder, and then into the <strong>project-sections</strong> folder. Click <strong>Upload files</strong> in the top right. Then drag-and-drop your newly named file. Once it's finished loading, click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	After a couple seconds of processing the file, Github will kick you back out to your market's main page of code. Navigate back into the <strong>projects</strong> folder, then into your <strong>specific project folder</strong> and from there into the <strong>project-sections</strong> folder.
</li>
<li>
	Now it's just a matter of following steps <strong>12</strong> to <strong>17</strong> above.
</li>
