# JAV-VR-JSON
## JAV Metadata Bundles for XBVR
### WIP - _where were you when R18 was kil?_

# FAQ
1. What is this?
Cooming stuff
2. Why did you do this?
Why not
3. How did you do this?
Yes
4. Why not write your own scraper?
Do I look like I know how to do that?
5. How do I use these? If you have to ask...

![image](https://user-images.githubusercontent.com/81622808/187829141-451b325a-d8a9-471b-932f-da200d01bbe0.png)

Like that.

**I am not responsible for you mass-deleting your database by ticking any of the other options _and then_ also ticking the `Overwrite existing data` option.** Version 2 of XBVR's metadata bundles always includes `null` entries for volumes, playlists, and sites when making a "scene only" bundle. But they probably sanitize their inputs. _Probably..._
```json
 "volumes": null,
 "playlists": null,
 "sites": null,
```

# Issues
## I added one of your bundles and it broke XBVR! I can't go past that scene in the Web UI!
I probably screwed up the image links or left a quotation mark unescaped and just manually corrected it in main.db. Open an issue and tell me which scene it was and I'll fix it. Re-importing the bundle after that will unbork the Web UI.
## Can you add x, y, or z scene?
No
## But my JAVfu is in it...
**No**
## Cool, I started doing the same thing too. Can I contribute?
Sure, open a pull request.
