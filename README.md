<img
  src="https://raw.githubusercontent.com/smsanchez1/Unknown-Interactive-header/main/Title.png" 
  width=128>


# Header for VSCode

This extension provides the TYPSA header integration in VS Code.

```bash
*****************************************************************************************************
*                                                                                                   *
*                                                    ▄• ▄▌ ▐ ▄ ▄ •▄  ▐ ▄       ▄▄▌ ▐ ▄▌ ▐ ▄         *
*                                                    █▪██▌•█▌▐██▌▄▌▪•█▌▐█▪     ██· █▌▐█•█▌▐█        * 
*                                                    █▌▐█▌▐█▐▐▌▐▀▀▄·▐█▐▐▌ ▄█▀▄ ██▪▐█▐▐▌▐█▐▐▌        * 
*    $FILENAME__________________________________     ▐█▄█▌██▐█▌▐█.█▌██▐█▌▐█▌.▐▌▐█▌██▐█▌██▐█▌        * 
*                                                     ▀▀▀ ▀▀ █▪·▀  ▀▀▀ █▪ ▀█▄▀▪ ▀▀▀▀ ▀▪▀▀ █▪        * 
*    By: $AUTHOR________________________________    .▄▄ ·       ·▄▄▄▄▄▄▄▄▄▄▌ ▐ ▄▌ ▄▄▄· ▄▄▄  ▄▄▄ .   *
*                                                   ▐█ ▀. ▪     ▐▄▄·•██  ██· █▌▐█▐█ ▀█ ▀▄ █·▀▄.▀·   *
*    Created: $CREATEDAT_________ by $CREATEDBY_    ▄▀▀▀█▄ ▄█▀▄ ██▪  ▐█.▪██▪▐█▐▐▌▄█▀▀█ ▐▀▀▄ ▐▀▀▪▄   *
*    Updated: $UPDATEDAT_________ by $UPDATEDBY_    ▐█▄▪▐█▐█▌.▐▌██▌. ▐█▌·▐█▌██▐█▌▐█ ▪▐▌▐█•█▌▐█▄▄▌   *
*                                                    ▀▀▀▀  ▀█▄▀▪▀▀▀  ▀▀▀  ▀▀▀▀ ▀▪ ▀  ▀ .▀  ▀ ▀▀▀    *
*                                                                                                   *
*****************************************************************************************************
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install TYPSAheader
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "TYPSAheader.username": string,
  "TYPSAheader.email": string
}
```


## Issues

In case of a bug, or missing feature, please create a [Github Pull Request](https://github.com/kube/vscode-42header/pulls).

## License

MIT
