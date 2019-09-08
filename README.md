# SleigHighlight 

Language highlighting for GHIDRA processor definition language Sleigh, because writing processor specification is tedious. So tedious that life might lose colors, everything becomes boring, you lose focus and at some point you'll go have a sandwich instead of writing some sick tools to reverse engineer  stuff.

Say no more, this is the tremendous difference that this extension makes.

 ## BORING

![boring](.images/boring.png)

## NON BORING

![non_boring](.images/non_boring.png)



Install this as you would do with any normal VScode extension. Nothing difficult.

# Development

To launch VScode with this extension loaded for development use:
`code --extensionDevelopmentPath=this_project_folder ./your_sleigh_project`

To debug the grammar use:
`Developer: Inspect TM Scopes`

To reload the grammar use:
`CTRL + R`

# Feature Development

It should be easy to port this extension to eclipse, as the underling tokenizer engine is the same (textmate). I haven't looked this up in more detail, but if you're interested feel free to ping me!