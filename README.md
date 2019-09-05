<a href="https://luehangs.site"><img src="https://luehangs.site/images/lh-blog-strip.jpg" alt="LueHsoft LueH LABS Lue Hang luehang"/></a>
<br/>
<br/>

<h1 align="center">
    React Native Page List
</h1>

An easy and simple to use React Native component that renders swipable performant pages with intelligent scroll/swipe detection to cushion rough guestures. Supporting both iOS and Android. Free and made possible along with costly maintenance and updates by [Lue Hang](https://www.facebook.com/lue.hang) (the author).

<br/>

---
<br/>

<h1 align="center">
    <a href="https://www.luehangs.site/lue_hang/projects/react-native-smart-page">
        <img src="https://www.luehangs.site/videos/react-native-smart-page-demo.gif" alt="react-native-smart-page"/>
    </a>
</h1>

<br/>
<br/>

# :link: Quick Links
- [Documentation](https://www.luehangs.site/lue_hang/projects/react-native-page-list)
- [Mobile Kit Marketplace](https://luehangs.site/marketplace/mobile-development)
- [React Native Development How To Dos](https://luehangs.site/blogs/react-native-development)
- [Chat](https://luehangs.site)

<br/>

---
<br/>

# :gem: Install

Type in the following to the command line to install the module.

```bash
$ npm install --save react-native-page-list
```

or

```bash
$ yarn add react-native-page-list
```

<br/>
<br/>
<br/>

---
<br/>
<br/>
<br/>

## :tada: Usage Example

Add an ``import`` to the top of the file.  At minimal, place `array` data into the `data` prop and render the pages using the `renderItem` prop.

> If you like [`react-native-page-list`](https://github.com/Luehang/react-native-page-list), please be sure to give it a star at [GitHub](https://github.com/Luehang/react-native-page-list). Thanks.

```javascript
import PageList from "react-native-page-list";
import { View, Image } from "react-native";

//...
render() {
    return (
        <PageList
            data={[
                { uri: "https://luehangs.site/pic-chat-app-images/pexels-photo-853168.jpeg" },
                { uri: "https://luehangs.site/pic-chat-app-images/animals-avian-beach-760984.jpg" },
                { uri: "https://luehangs.site/pic-chat-app-images/beautiful-beautiful-woman-beauty-9763.jpg" },
                { uri: "https://luehangs.site/pic-chat-app-images/photo-755745.jpeg" },
                { uri: "https://luehangs.site/pic-chat-app-images/photo-799443.jpeg" }
            ]}
            renderItem={({ item, index }) => {
                return (
                    <View key={index} style={{flex: 1, backgroundColor: "#000"}}>
                        <Image
                            source={{ uri: item.uri }}
                            style={{flex: 1}}
                            resizeMode="contain"
                        />
                    </View>
                );
            }}
        />
    );
}
//...
```

<br/>

---
<br/>

# :book: Full Documentation

Learn more about the installation and how to use this package in the updated [documentation](https://www.luehangs.site/lue_hang/projects/react-native-page-list) page.

<br/>
<br/>
<br/>

---
<br/>
<br/>
<br/>

## :santa: Author

<a href="https://www.facebook.com/lue.hang">
<img src="https://www.luehangs.site/images/lue-hang2018-circle-150px.png"/>
</a>

Free and made possible along with costly maintenance and updates by [Lue Hang](https://www.facebook.com/lue.hang) (the author).

<br/>
<br/>
<br/>

---
<br/>
<br/>
<br/>

## :clap: Contribute

[Pull requests](https://github.com/Luehang/react-native-page-list/pulls) are welcomed.

<br/>

### :tophat: Contributors

Contributors will be posted here.

<br/>

### :baby: Beginners

Not sure where to start, or a beginner? Take a look at the [issues page](https://github.com/Luehang/react-native-page-list/issues).

<br/>
<br/>
<a href="https://luehangs.site/marketplace/product/RN%20Posting%20Demo%20App%20Kit"><img src="https://luehangs.site/images/lh-mobile-strip.jpg" alt="LueHsoft LueH LABS Lue Hang luehang"/></a>
<br/>
<br/>

## :page_facing_up: License

MIT © [Lue Hang](https://luehangs.site), as found in the LICENSE file.
