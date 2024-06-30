# $isBoolean
Returns whether the provided text is a boolean or not.

> 🧙‍♂️ "true" means the text is a boolean, "false" means it isn't.

## Syntax
```
$isBoolean[Text]
```

### Parameters
- `Text` `(Type: String || Flag: Emptiable)`: The text to check.

### Supported Booleans
Positive | Negative 
-------- | --------
true | false
yes | no
on | off
enable | disable

## Example
```
$nomention
Is boolean?: `$isBoolean[$message]`
```

``` discord yaml
- user_id: 803569638084313098
  username: RainbowKey
  color: "#E67E22"
  content: |
    !example yes
- user_id: 1009018156494368798
  username: BDFD Support
  color: "#378afa"
  bot: true
  verified: true
  content: |
    Is boolean?: <code>true</code>
- user_id: 803569638084313098
  username: RainbowKey
  color: "#E67E22"
  content: |
    !example false
- user_id: 1009018156494368798
  username: BDFD Support
  color: "#378afa"
  bot: true
  verified: true
  content: |
    Is boolean?: <code>true</code>
- user_id: 803569638084313098
  username: RainbowKey
  color: "#E67E22"
  content: |
    !example text
- user_id: 1009018156494368798
  username: BDFD Support
  color: "#378afa"
  bot: true
  verified: true
  content: |
    Is boolean?: <code>false</code>
```
