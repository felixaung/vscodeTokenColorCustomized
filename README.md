# vscodeTokenColorCustomized

## I've had terrible experiences with the token color of every free VScode extension
## So i have decided to alter the token colors myself with the help of my fri graphic designer 

### You can copy and paste this format to your vscode > settings.json 
### Hoping you guys enjoy the colors 


#### Example 
scope can be find with inspect editor tokens and scopes

```text
public                                  6 chars
language	                              java
standard token type	                    Other
foreground	                          #EC8E2C
background	                          #0D1117
contrast ratio	                        7.63
font style	                            bold
semantic token type	                    modifier
foreground	                            storage.modifier.java
                                        storage
                                        storage.type
                                        { "foreground": "#ec8e2c" }
bold, italic, underline, strikethrough	keyword.control
                                        keyword
                                        { "foreground": "#f59043", "fontStyle": "bold" }
textmate scopes	                        storage.modifier.java
                                        meta.method.java    
                                        meta.class.body.java
                                        meta.class.java
                                        source.java 

```


``` json

      {
        "scope": ["keyword"],
        "settings": {
          "foreground": "#f59043",
          "fontStyle": "bold"
        }
      },
```

