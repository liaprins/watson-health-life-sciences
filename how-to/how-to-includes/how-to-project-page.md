<li>
	Download the template of files and folders for starting a new project page from <a href="https://ibm.box.com/v/new-project-page-template" target="_blank">Box</a> and unzip the compressed folder.
</li>
<li>
	Rename the folder with your project's acronym in lowercase.
	<ul>
		<li>
			For example, Watson for Patient Safety goes by <strong>wps</strong>.
		</li>
		<li>
			Make sure everything is lowercase. Avoid any spaces or special characters like "!" or "@".
		</li>
	</ul>
</li>
<li>
	Go to the <a href="https://github.ibm.com{{ site.baseurl }}/tree/gh-pages" target="_blank">Github project for your market page</a>. Open the <strong>projects</strong> folder.
</li>
<li>
	Click <strong>Upload files</strong> in the top right. Then drag-and-drop your newly named folder as a whole. Once all files have finished loading, click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	After a couple seconds of processing the files, Github will kick you back out to your market's main page of code. Navigate back into the <strong>projects</strong> folder and into <strong>your newly added folder</strong>.
</li>
<li>
	Open <strong>index.md</strong>, and click the pencil icon in the top right corner to edit its contents.
</li>
<li>
	Supply content for each of the prompts listed between the <span class="code">---</span> borders on top and bottom, as described below. Maintain a space between the colon and your response. Leave the rest of the code on the page alone.
	<ul>
		<li>
			<strong>title: </strong>This is the full name for your project, like "Watson for Patient Safety".
		</li>
		<li>
			<strong>shortname: </strong>This is the acronym for your project that you named the project folder after in step 2. Be sure to type it in all caps here!
		</li>
		<li>
			<strong>team_members: </strong>Add a list of everyone on the design team for this project. Make sure they already have a profile on your <a href="{{ site.baseurl }}#team" target="_blank">offering's market page</a>. If they don't, you'll need to create a profile for them there. Follow the steps to <strong><a href="{{ site.baseurl }}{{ page.url }}#market-member">Add a new team member to a market page</a></strong> above for guidance. The name you add here must match the exact name used in the <span class="code">name:</span> row of the team member's market profile, character-for-character.
		</li>
	</ul>
</li>
<li>
	Click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	Go back out to <strong>your project</strong> folder, and then into the <strong>project-includes</strong> folder. Open the <strong>project-what-is.md</strong> file.
	<ul>
		<li>
			You can get to <strong>your project</strong> folder by clicking the blue link to it in the breadcrumb at the top left.
		</li>
	</ul>
</li>
<li>
	Leave the top line of text within <strong>project-what-is.md</strong> alone, and replace <span class="code">[ADD A DESCRIPTION OF YOUR PROJECT HERE: WHO IT SERVES, HOW IT HELPS THEM, ETC.]</span> with a description! 
</li>
<li>
	Click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	Now you have a basic project page with a description and profiles of the designers involved. Navigate to your <a href="{{ site.baseurl }}#offerings" target="_blank">market page's offering section</a> and you should see your project in the list. Click the link to visit your new project page!
	<ul>
		<li>
			If it isn't showing up, try refreshing the cache for the page by pressing <strong>command + shift + R</strong>.
		</li>
		<li>
			You can add more sections of content to your page if you want, too. Follow the steps to <strong><a href="{{ site.baseurl }}{{ page.url }}#project-section">Add a section to a project page</a></strong> below for guidance.
		</li>
	</ul>
</li>
