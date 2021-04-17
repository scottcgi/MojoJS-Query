## MojoJS-Query v2.0.0

MojoJS-Query is a pure javascript **CSS Selector** engine. 

It not only supports **full CSS3 Selectors** and more, and **easy-to-extend**, but also has very **simple**, **beautiful**, **easy-to-understand** code structure and implementation ideas.

* Released versions in [releases](https://github.com/scottcgi/MojoJS-Query/releases).
* Release changes in [ChangeLog](https://github.com/scottcgi/MojoJS-Query/blob/master/ChangeLog.md).

The [Online Speed-Test](https://scottcgi.github.io/MojoJS-Query/speed-test/index.html) shows the support selectors and speed comparison with native query.

## License

MojoJS-Query is licensed under the [MIT License](https://github.com/scottcgi/MojoJS-Query/blob/master/LICENSE "MojoJS-Query Under MIT License").


## How to use

```js
/**
 * Query HTMLElements by css seletor and context.
 * 
 * @param  {String}                                                          selector
 * @param  {String (selector) | HTMLElement | Array<HTMLElement> | NodeList} context (optional)
 * @return {Array<HTMLElement>}                                              HTMLElements Array
 */
 MojoJS.query(selector, context);
```

## Support CSS Selectors

```css
*
#id
E
E.cls
E F
E > F
E + F
E ~ F

E[foo]  
E[foo="bar"]    
E[foo~="bar"]   
E[foo^="bar"]   
E[foo$="bar"]   
E[foo*="bar"]   
E[foo|="en"]

E:checked
E:disabled
E:enabled
E:empty

E:only-child
E:last-child
E:first-child
E:first-of-type
E:last-of-type
E:only-of-type

E:not(s)
E:nth-child(n)
E:nth-last-child(n)
E:nth-of-type(n)
E:nth-last-of-type(n)

// Extra Selectors

:not(E)
:not(E.cls)
:not(:not(E,F))

:has(E)
:has(E.cls)
:has(:not(E,F))
:has(E > F)

[NAME!=VALUE]
:contains(TEXT)
:selected

:first
:last
:even
:odd
:nth
```

## Support

If the source code is **useful** or **helpful** for you, maybe buy me a coffee via **Sponsor Button**.
