# StreamWatch
[![StreamWatch Image](.github/StreamWatch.png)](https://docs.StreamWatch.lol)  

**I *do not* endorse piracy of any kind I simply enjoy programming and large user counts.**

## Links And Resources
| Service        | Link                                                             | Source Code                                              |
|----------------|------------------------------------------------------------------|----------------------------------------------------------|
| StreamWatch Docs | [sudo-docs](https://sussy-code.github.io/docs)                   | [source code](https://github.com/sussy-code/docs)        |
| Extension      | [extension](https://sussy-code.github.io/docs/extension)         | [source code](https://github.com/sussy-code/browser-ext) |
| Proxy          | [sudo-proxy](https://sudo-proxy.up.railway.app)                  | [source code](https://github.com/sussy-code/sudo-proxy)  |             
| Backend        | [sudo-backend](https://backend.StreamWatch.lol)                    | [source code](https://github.com/sussy-code/backend)     |
| Frontend       | [StreamWatch](https://StreamWatch.lol), [2](https://flix.kanded.xyz) | [source code](https://github.com/sussy-code/smov)        |

***I provide these if you are not able to host yourself, though I do encourage hosting the frontend.***


## Referrers
- [Piracy Subreddit Megathread](https://www.reddit.com/r/Piracy/s/iymSloEpXn)
- [Toon's Instances](https://erynith.github.io/movie-web-instances)
- [StreamWatch docs](https://sussy-code.github.io/docs)
- [StreamWatch Discord](https://discord.gg/r5cYshWM4G)
- Search Engines: DuckDuckGo, Bing, Google
- Rentry.co


## Running Locally
Type the following commands into your terminal / command line to run StreamWatch locally
```bash
git clone https://github.com/sussy-code/smov.git
cd smov
git pull
pnpm install
pnpm run dev
```
Then you can visit the local instance [here](http://localhost:5173) or, at local host on port 5173.


## Updating a StreamWatch Instance
To update a StreamWatch instance you can type the below commands into a terminal at the root of your project.
```bash
git remote add upstream https://github.com/sussy-code/smov.git
git fetch upstream # Grab the contents of the new remote source
git checkout <YOUR_MAIN_BRANCH>  # Most likely this would be `origin/main`
git merge upstream/main
# * Fix any conflicts present during merge *
git add .  # Add all changes made during merge and conflict fixing
git commit -m "Update StreamWatch instance (merge upstream/main)"
git push  # Push to YOUR repository
```


## Contact Me
**Email:** *[dev@StreamWatch.lol](mailto:dev@StreamWatch.lol)* 
