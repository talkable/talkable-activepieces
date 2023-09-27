<h1 align="center">
  <a
    target="_blank"
    href="https://activepieces.com"
  >
    <img
      align="center"
      alt="Activepieces"
src="https://github.com/activepieces/activepieces/assets/1812998/76c97441-c285-4480-bc75-30a0c73ed340"
      style="width:100%;"
    />

  </a>
</h1>

<br>
<br>

# ✨ Docker Compose

To get up and running quickly with Activepieces, follow the instruction [here](https://www.activepieces.com/docs/install/options/docker-compose).

<br>
<br>

<br>
<br>

# ✨ Update activepieces

To update the app:
<ol>
    <li>Updatethe tag of the service (activepieces, redis or postgres) in docker-compose.yml file.
The version of the service must match the released tag of services from the docker-compose.yml file [here](https://github.com/activepieces/activepieces).</li>
    <li>Commit-push the changes.</li>
    <li>Login into the server.</li>
    <li>Change directory to talkable-activepieces and pull last changes.</li>
    <li>Run 
<pre>
<code>
sh tools/update.sh
</code>
</pre></li>
    <!-- And so on... -->
</ol>
<br>
<br>

<br>
<br>
