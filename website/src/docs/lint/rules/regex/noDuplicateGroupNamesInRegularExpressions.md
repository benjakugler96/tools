---
title: Lint Rule regex/noDuplicateGroupNamesInRegularExpressions
layout: layouts/rule.liquid
description: MISSING DOCUMENTATION
eleventyNavigation:
	key: lint-rules/regex/noDuplicateGroupNamesInRegularExpressions
	parent: lint-rules
	title: regex/noDuplicateGroupNamesInRegularExpressions
---

# regex/noDuplicateGroupNamesInRegularExpressions

<!-- GENERATED:START(hash:0c842939a2a049e8cdb4f0be47baab529ffcaf37,id:description) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules` to update. -->
MISSING DOCUMENTATION
<!-- GENERATED:END(id:description) -->

<!-- GENERATED:START(hash:0df41591e0b7a6fb86e8f7f8d7f20e407af23d2e,id:examples) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules-docs` to update. -->
## Examples

### Invalid

{% raw %}<pre class="language-js"><code class="language-js"><span class="token regex">/(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;day&gt;[0-9])-([0-9])-(?&lt;month&gt;[0-9])/</span></code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.ts:1:1</span> <strong>lint/regex/noDuplicateGroupNamesInRegularExpressions</strong> ━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Avoid duplicate group names. Check the </span><span style="color: Tomato;"><strong>month</strong></span><span style="color: Tomato;"> group.</span>

    <span class="token regex">/(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;day</span>
    <span class="token regex">  &gt;[0-9])-([0-9])-(?&lt;month&gt;[0-9])/</span>
    <span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Defined already here</span>

    <span class="token regex">/(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;day</span>
    <span class="token regex">  &gt;[0-9])-([0-9])-(?&lt;month&gt;[0-9])/</span>
    <span style="color: Tomato;"><strong>^</strong></span>

    <span class="token regex">/(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;day</span>
    <span class="token regex">  &gt;[0-9])-([0-9])-(?&lt;month&gt;[0-9])/</span>
    <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.ts:1:17</span> <strong>lint/regex/noDuplicateGroupNamesInRegularExpressions</strong> ━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Avoid duplicate group names. Check the </span><span style="color: Tomato;"><strong>year</strong></span><span style="color: Tomato;"> group.</span>

    <span class="token regex">/(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;day</span>
    <span class="token regex">  &gt;[0-9])-([0-9])-(?&lt;month&gt;[0-9])/</span>
    <span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: rgb(38, 148, 255);">ℹ </span></strong><span style="color: rgb(38, 148, 255);">Defined already here</span>

    <span class="token regex">/(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;month&gt;[0-9])-(?&lt;year&gt;[0-9])-(?&lt;day</span>
    <span class="token regex">  &gt;[0-9])-([0-9])-(?&lt;month&gt;[0-9])/</span>
    <span style="color: Tomato;"><strong>^</strong></span>

</code></pre>{% endraw %}
<!-- GENERATED:END(id:examples) -->
