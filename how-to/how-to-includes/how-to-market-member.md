<li>
	Obtain (or manually crop) a perfectly square photo of the new team member; at a minimum 150px x 150px.
	<ul>
		<li>
			Avoid using photos that are significantly larger, as they'll slow the page load.
		</li>
		<li>
			Non-square photos will be squished when the browser renders them, distorting the image!
		</li>
	</ul>
</li>
<li>
	Name the image file with the new team member's first name, or something similarly short, descriptive, and appropriate.
	<ul>
		<li>
			Make sure everything is lowercase. Avoid any spaces or special characters like "!" or "@".
		</li>
		<li>
			Take note of the final file name and its extension, as you'll need it soon!
		</li>
	</ul>
</li>
<li>
	Go to the <a href="https://github.ibm.com{{ site.baseurl }}/tree/gh-pages" target="_blank">Github project for your market page</a>. Open the <strong>_profiles</strong> folder, and then the <strong>profile-images</strong> folder.
</li>
<li>
	Click <strong>Upload files</strong> in the top right. Then drag-and-drop or navigate to the image file. Once the file has finished loading, click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	Go back out to the <strong>_profiles</strong> folder.
	<ul>
		<li>
			You can get there from within the <strong>profile-images</strong> folder by clicking the blue <strong>_profiles</strong> link in the breadcrumb at the top left.
		</li>
	</ul>
</li>
<li>
	Click <strong>Create new file</strong> in the top right. To keep things simple, name this new file the same thing you named the image file, but with the extension <strong>.md</strong>.
	<ul>
		<li>
			Take a look at the file names in the folder already. They may be prepended by a number and an underscore or a date, like <strong>03</strong> or <strong>20160316</strong>. This is to keep the profiles of team members in a certain order when they appear on the market page (for example the date they joined the team or IBM). Names without a numerical prefix will appear in alphabetical order.
		</li>
		<li>
			Prefix the image file with the next number or the date they joined, if needed.
		</li>
	</ul>
</li>
<li>
	In the body of the file, paste the following text: <br />
	<span class="code">
		---<br />
		name: <br />
		image_file_name: <br />
		personality_acronym: <br />
		personality_word: <br />
		role: <br />
		slack_handle_sans_at: <br />
		email: <br />
		---
	</span>
	<ul>
		<li>
			Be sure to include the three dashes at the top and bottom!
		</li>
	</ul>
</li>
<li>	
	Supply content for each of the prompts. Maintain a space between the colon and your response. You can leave some blank and come back to edit them later if needed.
	<ul>
		<li>
			<strong>name: </strong>The full name of the new team member, with proper capitalization.
		</li>
		<li>
			<strong>image_file_name: </strong>Here's where you enter the name you gave the image file, including the extension.
		</li>
		<li>
			<strong>personality_acronym: </strong>If you're including personality type on roll-over, have your new team member take the personality quiz from <a href="https://www.16personalities.com/free-personality-test" target="_blank">16 Personalities</a>, and add their 4-letter personality type here in all caps.
		</li>
		<li>
			<strong>personality_word: </strong><a href="https://www.16personalities.com/personality-types" target="_blank">The name of their personality type.</a>
		</li>
		<li>
			<strong>role: </strong>The role of the new team member, for example "UX Designer".
		</li>
		<li>
			<strong>slack_handle_sans_at: </strong>Add their Slack handle here; with<em>out</em> the "@" symbol.
		</li>
		<li>
			<strong>email: </strong>The new team member's IBM email address.
		</li>
	</ul>
</li>
<li>
	Click the green <strong>Commit changes</strong> button in the bottom left.
</li>
<li>
	Wait a couple minutes for the server to process your updates, and then take a look at the <strong><a href="{{ site.baseurl }}#team" target="_blank">Team members</a></strong> section of your market page. Verify that all the content you added is correct.
	<ul>
		<li>
			If the new profile isn't showing up, try refreshing the cache for the page by pressing <strong>command + shift + R</strong>.
		</li>
		<li>
			If you need to change anything, navigate back to the new file within the <strong>_profiles</strong> folder, click the pencil icon in the top right, make your corrections, and re-commit the file via the green <strong>Commit changes</strong> button.
		</li>
	</ul>
</li>
