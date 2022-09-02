Application Programming Interfaces (APIs) are constructs made available in 
programming languages to allow developers to create complex 
functionality more easily. They abstract more complex code away from 
you, providing some easier syntax to use in its place.

As a real-world example, think about the electricity supply in your house, apartment, or other 
dwellings. If you want to use an appliance in your house, you plug it 
into a plug socket and it works. You don't try to wire it directly into 
the power supply — to do so would be really inefficient and, if you are 
not an electrician, difficult and dangerous to attempt.

In the same way, if you want to say, program some 3D graphics, it is a lot easier to do it using an API written in a higher-level language such as JavaScript or Python, rather than try to directly write low level code (say C or C++) that directly controls the computer's GPU or other graphics functions.

think as the api is the waitress  the kitchen is the resource and the place where complex things made and the client is the place where going to use these already made resources

![https://apipheny.io/wp-content/uploads/2020/10/api-waiter-1.png](https://apipheny.io/wp-content/uploads/2020/10/api-waiter-1.png)

## [What can APIs do?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction#what_can_apis_do)

There
 are a huge number of APIs available in modern browsers that allow you 
to do a wide variety of things in your code. You can see this by taking a
 look at the [MDN APIs index page](https://developer.mozilla.org/en-US/docs/Web/API).

### [Common browser APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction#common_browser_apis)

In
 particular, the most common categories of browser APIs you'll use (and 
which we'll cover in this module in greater detail) are:

- **APIs for manipulating documents** loaded into the browser. The most obvious example is the [DOM (Document Object Model) API](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model), which allows you to manipulate HTML and CSS — creating, removing and
changing HTML, dynamically applying new styles to your page, etc. Every
time you see a popup window appear on a page or some new content
displayed, for example, that's the DOM in action. Find out more about
these types of API in [Manipulating documents](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents).
- **APIs that fetch data from the server** to update
small sections of a webpage on their own are very commonly used. This
seemingly small detail has had a huge impact on the performance and
behavior of sites — if you just need to update a stock listing or list
of available new stories, doing it instantly without having to reload
the whole entire page from the server can make the site or app feel much more responsive and "snappy". The main API used for this is the [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API), although older code might still use the `[XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)` API. You may also come across the term **Ajax**, which describes this technique. Find out more about such APIs in [Fetching data from the server](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data).
- **APIs for drawing and manipulating graphics** are widely supported in browsers — the most popular ones are [Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) and [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API), which allow you to programmatically update the pixel data contained in an HTML `[<canvas>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas)` element to create 2D and 3D scenes. For example, you might draw shapes
such as rectangles or circles, import an image onto the canvas, and
apply a filter to it such as sepia or grayscale using the Canvas API, or create a complex 3D scene with lighting and textures using WebGL. Such
APIs are often combined with APIs for creating animation loops (such as `[window.requestAnimationFrame()](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame)`) and others to make constantly updating scenes like cartoons and games.

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction)
what is json data
# what is json data

JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax.

It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa).

[https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
{
  "squadName": "Super hero squad",
  "homeTown": "Metro City",
  "formed": 2016,
  "secretBase": "Super tower",
  "active": true,
  "members": [
    {
      "name": "Molecule Man",
      "age": 29,
      "secretIdentity": "Dan Jukes",
      "powers": [
        "Radiation resistance",
        "Turning tiny",
        "Radiation blast"
      ]
    },
    {
      "name": "Madame Uppercut",
      "age": 39,
      "secretIdentity": "Jane Wilson",
      "powers": [
        "Million tonne punch",
        "Damage resistance",
        "Superhuman reflexes"
      ]
    },
    {
      "name": "Eternal Flame",
      "age": 1000000,
      "secretIdentity": "Unknown",
      "powers": [
        "Immortality",
        "Heat Immunity",
        "Inferno",
        "Teleportation",
        "Interdimensional travel"
      ]
    }
  ]
}