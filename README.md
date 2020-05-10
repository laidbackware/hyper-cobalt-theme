# Cobalt Theme for [Hyper](https://hyper.is) <img width="32" alt="Hyper Material Theme" src="https://cloud.githubusercontent.com/assets/10454741/21241774/9172ddb6-c311-11e6-91ee-e4225ab9560a.gif">

<img width="480" alt="Hyper Material Theme" src="https://cloud.githubusercontent.com/assets/10454741/21243792/bbaf728e-c31a-11e6-972f-0995e77a32a0.png">

## 1. Installation

Just edit your `~/.hyper.js` file (Hyper > Preferences...) and add `hyper-material-theme` to `plugins: []` array.

```js
...
plugins: ['hyper-material-theme'],
...
```


## 2. Configuration
This theme provides settings that you MUST add in your `~/.hyper.js` file **inside the `config` key** the colors object.

```js
    config: {
      MaterialTheme: {
          // Set the theme variant,
          // OPTIONS: 'Darker', 'Lighter', ''
          theme: '',
  
          // [Optional] Set the rgba() app background opacity, useful when enableVibrance is true
          // OPTIONS: From 0.1 to 1
          backgroundOpacity: '1',
  
          // [Optional] Set the accent color for the current active tab
          accentColor: '#64FFDA',
  
          // [Optional] Mac Only. Need restart. Enable the vibrance and blurred background
          // OPTIONS: 'dark', 'ultra-dark', 'bright'
          // NOTE: The backgroundOpacity should be between 0.1 and 0.9 to see the effect.
          vibrancy: 'dark'
      },

      ...
    }

    ...
```
**Then restart the app**

## 3. Customizable props
There are also some Hyper's customizable props directly from the `config` prop that will override the ones within the Material Theme default configurations:

```js
{
  config: {
    cursorColor: '',
    padding: '',
    termCss: ''
    css: ''
  }
}
```
