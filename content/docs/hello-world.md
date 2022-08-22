---
id: hello-world
title: Hello World
permalink: docs/hello-world.html
prev: cdn-links.html
next: introducing-jsx.html
---

Mfano mdogo wa React unaonekana hivi:

```jsx
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<h1>Hello, world!</h1>);
```

Inaonyesha kichwa kinachosema "Hello, world!" kwenye ukurasa.

**[Try it on CodePen](https://codepen.io/gaearon/pen/rrpgNB?editors=1010)**

Bonyeza kiunga hapa juu kufungua hariri ya mkondoni. Jisikie huru kufanya mabadiliko kadhaa, na uone jinsi zinavyoathiri pato. Kurasa nyingi katika mwongozo huu zitakuwa na mifano ya kuhariri kama hii.


## Jinsi ya kusoma Mwongozo huu {#how-to-read-this-guide}

Katika mwongozo huu, tutachunguza vitengo vya ujenzi wa programu za React: elements na components. Utakapozijua, utaweza kuunda programu ngumu kutoka kwa vipande vidogo vinavyoweza kutumika tena.

>Kidokezo
>
>Mwongozo huu umeundwa kwa watu ambao wanapendelea **kujifunza dhana kwa hatua**. Ikiwa unapenda kujifunza kwa kufanya, angalia [mafunzo yetu ya vitendo](/tutorial/tutorial.html). Unaweza kupata mwongozo huu inasaidiana na mafunzo hayo.

Hii ndio sura ya kwanza katika mwongozo wa hatua kwa hatua kuhusu dhana kuu za React. Unaweza kupata orodha ya sura zake zote kwenye upau wa kando ya urambazaji. Ikiwa unasoma kutoka kwa simu ya rununu, unaweza kufikia urambazaji kwa kubonyeza kitufe kwenye kona ya chini ya kulia ya skrini yako.

Kila sura katika mwongozo huu inaendeleza maarifa yaliyoletwa katika sura za mapema. **Unaweza kujifunza React zaidi kwa kusoma safu za mwongozo wa "Dhana kuu" zinavyoonekana kwenye upau wa pembeni.** Kwa mfano, [“Introducing JSX”](/docs/introducing-jsx.html) ndio sura inayofuata baada ya hii.

## Dhana ya Kiwango cha Maarifa {#knowledge-level-assumptions}

React ni maktaba ya JavaScript, kwa hivyo tunadhania kuwa una ufahamu wa kimsingi wa lugha ya JavaScript. **Ikiwa haujihisi kijasiri, tunapendekeza [kupitia mwongozo wa JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) kuangalia kiwango chako cha maarifa** ili kikuwezeshe kufuata mwongozo huu bila kupotea. Itakuchukua kati ya dakika 30 au saa moja, lakini matokeo yake hautahisi kana kwamba unajifunza lugha yote mawili ya React na JavaScript wakati mmoja.

>Kumbuka
>
<<<<<<< HEAD
>Mwongozo huu wakati mwingine hutumia mfumo mpya wa JavaScript kwenye mifano. Ikiwa haujajihusisha na JavaScript katika miaka michache iliyopita, [nukta hizi tatu](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) zinapaswa kukupa njia zaidi.
=======
>This guide occasionally uses some newer JavaScript syntax in the examples. If you haven't worked with JavaScript in the last few years, [these three points](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) should get you most of the way.
>>>>>>> 37cf98d075de3133b5ae69fe80fbecb6a742530a


## Tuanze! {#lets-get-started}

Endelea kwa kushuka chini kwenye ukurasa, utapata kiunga cha sura inayofuata ya mwongozo huu mbele ya wavuti wa tovuti.


