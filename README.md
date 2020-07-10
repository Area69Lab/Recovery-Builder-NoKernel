# Building recovery online made easy #

## Important notice ##
### Users reported build errors forking to own account. ###
### To fix this, create a new organization, fork to the new organization. This fixes the problem, for now.

#### What this is ####

This is an easy way for recovery maintainers or anyone who's interested in building recoveries to finish their dream without a server.

This works with GitHub actions, thank GitHub not me.

#### How to use ####

Here are some useful notes to using this tool brewed with black magic.

1. Fork the repo to a organization

2. Set the variables, as listed below.

Update : If you don't understand the manifest variable, check [this](https://github.com/Area69Lab/Recovery-builder/blob/master/guide.md)

Some variables that you'd like to set:

```MANIFEST : Link to your recovery manifest, Google it if you don't know what this is```

```DEVICE : Most likely your device codename, e.g. rosy, sakura, curtana, etc.```

```DT_LINK : Link to your recovery device tree.```

```DT_PATH : Path to clone your device tree ```

```TARGET : recoveryimage or bootimage, depending on if your phone has a recovery partition or not ```

3. Go to actions tab, enable workflows.

4. Star the repo, go to actions tab again, and let black magic go brrr.

If you don't know any of these, **Ask [Google](https://www.google.com) or someone who builds recoveries**, I don't provide TWRP building support.

You'd also like to do edits on your recovery device tree first if your recovery needs that (e.g. SHRP, etc.)

#### Credits and thanks and stuff like that ####

Made with blek magic by [***Jamie***](https://t.me/henloboi)

Infinite help from [***ElytrA8***](t.me/ElytrA8)

Recovery building help from [***Pulkit***](t.me/Pulkit077)

And lastly, all TWRP compiling help from Google.

Enjoy buildbotting.
