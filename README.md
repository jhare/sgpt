# sgpt
shell gpt access

manage keys at https://platform.openai.com/account/api-keys

**usage**
`sgpt "what is a minimal html5 document"`

```
jhare@codysomenumber:~$ sgpt "what is a minimal html5 document"
<!DOCTYPE html>
<html>
 <head>
 <title>Page Title</title>
 </head>
 <body>
 </body>
</html>
jhare@codysomenumber:~$
```

execute as root user
```
git clone git@github.com:jhare/sgpt
cd sgpt

cp ./sgpt /usr/share/bin
cp ./.sgpt ~/.config
```

**dependencies**
```
sudo apt install jq xclip curl git
```
