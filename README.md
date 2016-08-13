## me-lazyload
Images lazyload directive for angular.

### Demo
Demo Site: http://treri.github.io/me-lazyload 

### Basic Usage
1. include me-lazyload.js as dependence.

        var app = angular.module('myApp', ['me-lazyload'])

2. instead `src` with `lazy-src`.

        <img lazy-src="{{imgUrl}}" alt="" />

3. All Done!

### Optional Parameters
Additional parameters can be added, example:

         <img lazy-src="{{imgUrl}}" animate-visible="true" animate-speed="0.5s" alt="" />

The following is a list of all the additional parameters:

| Paramater | Remark | Value (Example) | Default Value |
| --- | --- | --- | --- |
| `animate-visible` | If set true, all images (include those initially visible)  will be animated. Please note that by default initial visible images will be displayed immediately without fading | "true" | "false" |
| `animate-speed` | The speed of the animation in seconds or milliseconds | "0.5s" | "1s" |

### License
MIT