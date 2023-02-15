# openaicli
yet another cli to access openai chat and image generator from bash


# Usage

```
openai "a chat prompt"
```

--> Return the response to terminal

or

```
openai "image:an imagepromt"
```

--> Returns the url to the generated imagem

or just:

```
openai
```

--> Enters a loop to keep generating chat or images. When inside the loop the image gets downloaded to ~/Downloads and opened with preview (macOS)



## install

just copy openai to your /usr/bin or where you want it
and make it executable:

```
chmod +x openai
```

## Dependencies

* jq
* curl

This command expects there is a line:

```
export OPENAI_KEY=xxxxxxxxxxxxx
```

in your .bash_profile.

