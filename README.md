# fb-downloader v1.0.0

#### Downloads HD videos from Facebook

##### Developed By

[![N|Solid](https://blog.tcmhack.in/wp-content/uploads/2019/04/cropped-tcmhack-logo.png)](https://admin.tcmhack.in)

![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

FB Downloader is a simple JavaScript package which provides a facility to download videos form Facebook in available quality

It is open source with a [public repository](https://github.com/tikamchand06/fb-downloader.git) on GitHub.

## Installation

You can install this package via below command

```sh
npm i fb-downloader
```

## Example

```sh
import getFBInfo from "fb-downloader"

const info = await getFBInfo("https://www.facebook.com/watch?v=272591278381388");
console.log(info);
```

The output will be

```sh
{
  sd: 'https://video.fjai5-1.fna.fbcdn.net/v/t42.1790-2/275801506_172276165130059_885167449675909210_n.mp4?_nc_cat=104&ccb=1-5&_nc_sid=985c63&efg=eyJybHIiOjMxMSwicmxhIjo1MTIsInZlbmNvZGVfdGFnIjoic3ZlX3NkIn0%3D&_nc_ohc=kJrobRAXbxoAX8VEdvi&rl=311&vabr=173&_nc_ht=video.fjai5-1.fna&oh=00_AT-wGlrbVVdKYiAdjGQd5hZ2YjMkLqshdk9-o94DZaXzCg&oe=6246C62C',
  hd: 'https://scontent.fjai5-1.fna.fbcdn.net/v/t66.36240-6/120162803_2190017344494785_2810101870338104985_n.mp4?_nc_cat=108&ccb=1-5&_nc_sid=985c63&efg=eyJybHIiOjE1MDAsInJsYSI6MTAyNCwidmVuY29kZV90YWciOiJvZXBfaGQifQ%3D%3D&_nc_ohc=Y4spcb6Zt4AAX-rAr77&rl=1500&vabr=239&_nc_ht=scontent.fjai5-1.fna&oh=00_AT9b4aIJp5aWOP4M4trMiXyxVWE7igHTfCIleKMUIvZhSQ&oe=624AF2FD',
  title: '&#x2022; Date Gone Wrong &#x1f606;&#x1f606;&#x1f926;&#x200d;&#x2642;&#xfe0f;',
  thumbnail: 'https://scontent.fjai5-1.fna.fbcdn.net/v/t15.5256-10/275173684_1165104900988683_8395349523361992483_n.jpg?stp=dst-jpg_p960x960&_nc_cat=101&ccb=1-5&_nc_sid=df419e&_nc_ohc=CR8wn4I3yl4AX_MPj1E&_nc_ht=scontent.fjai5-1.fna&oh=00_AT_W53vbCs12eZVJ3tKC7rD7mhTi0oTHP_RMP9ADQJ8c8w&oe=624BBB48'
}
```
