---
id: button
title: Button
category: Components
permalink: docs/button.html
---
<div><div><p>A basic button component that should render nicely on any platform. Supports
a minimal level of customization.</p><span><center><img src="img/buttonExample.png"></center>

</span><p>If this button doesn't look right for your app, you can build your own
button using <a href="docs/touchableopacity.html" target="_blank">TouchableOpacity</a>
or <a href="docs/touchablenativefeedback.html" target="_blank">TouchableNativeFeedback</a>.
For inspiration, look at the <a href="https://github.com/facebook/react-native/blob/master/Libraries/Components/Button.js" target="_blank">source code for this button component</a>.
Or, take a look at the <a href="https://js.coach/react-native?search=button" target="_blank">wide variety of button components built by the community</a>.</p><p>Example usage:</p><div class="prism language-javascript"><span class="token operator">&lt;</span>Button
  onPress<span class="token operator">=</span><span class="token punctuation">{</span>onPressLearnMore<span class="token punctuation">}</span>
  title<span class="token operator">=</span><span class="token string">"Learn More"</span>
  color<span class="token operator">=</span><span class="token string">"#841584"</span>
  accessibilityLabel<span class="token operator">=</span><span class="token string">"Learn more about this purple button"</span>
<span class="token operator">/</span><span class="token operator">&gt;</span></div></div><h3><a class="anchor" name="props"></a>Props <a class="hash-link" href="docs/button.html#props">#</a></h3><div class="props"><div class="prop"><h4 class="propTitle"><a class="anchor" name="accessibilitylabel"></a>accessibilityLabel?: <span class="propType"><span>?string</span></span> <a class="hash-link" href="docs/button.html#accessibilitylabel">#</a></h4><div><p>Text to display for blindness accessibility features</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="color"></a>color?: <span class="propType"><span>?string</span></span> <a class="hash-link" href="docs/button.html#color">#</a></h4><div><p>Color of the text (iOS), or background color of the button (Android)</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="disabled"></a>disabled?: <span class="propType"><span>?boolean</span></span> <a class="hash-link" href="docs/button.html#disabled">#</a></h4><div><p>If true, disable all interactions for this component.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="onpress"></a>onPress: <span class="propType">() =&gt; any</span> <a class="hash-link" href="docs/button.html#onpress">#</a></h4><div><p>Handler to be called when the user taps the button</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="testid"></a>testID?: <span class="propType"><span>?string</span></span> <a class="hash-link" href="docs/button.html#testid">#</a></h4><div><p>Used to locate this view in end-to-end tests.</p></div></div><div class="prop"><h4 class="propTitle"><a class="anchor" name="title"></a>title: <span class="propType">string</span> <a class="hash-link" href="docs/button.html#title">#</a></h4><div><p>Text to display inside the button</p></div></div></div></div>