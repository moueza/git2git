# git2git
git migration from local git (Egit) to Github(remote)<BR>
Eclipse plugin<BR>
The whole subtlety is that Github may have been created(remotes add in Egit) after local git.<BR>
<ul>
<li>So local timestamps must be lost in remote repo but the series can be reflected by tag </li>
<li>OR successive commits can be epsilon(1 second, 10 seconds,or else)commit reproducted  </li> 
<li>OR branch series reproducted. </li>
<li>OR the true timing can be reflected by a field in commit comment or tag comment<BR></li>
</ul>
