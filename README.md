# pages-tunnel
Based on [this awesome thingy](https://github.com/Karlheinzniebuhr/ghpages-fileserver).

This project lets you easily get an [Underground](https://github.com/undergroundstore/Underground) tunnel running on GitHub's infrastructure, eliminating the need for you to own and maintain server technology. Still not convinced? The Rebirth-Devs team (us weirdos who made Underground) use it for our tunnels!

## Setup:
  - Open [GitHub web](https://github.com) and [fork this repository](https://github.com/undergroundstore/pages-tunnel/fork).
  - Open the fork, still on [GitHub.com](https://github.com).
  - Navigate to the settings panel.
  - On the left pane, select `Pages`.
  - Change the `source` to the `master` branch as shown:
  ![image](https://user-images.githubusercontent.com/77066742/145821999-49ac135f-9481-4f0c-a86c-1922dada2d1d.png)
  - Click `Save`.
  - Wait for GitHub's runners to deploy the site.
  
You can now edit the files in the `/resources/` directory in your repository, either on [GitHub.com](https://github.com) or using a code editor like [VScodium](https://vscodium.com), to change the files on the server. Note that GitHub Pages will have to re-deploy the site every time you `push` changes to or `merge` changes into `master`.

For the GitLab-compatible version, see [this GitGud.io repository](https://gitgud.io/underground/pages-tunnel-gitlab-pages).
