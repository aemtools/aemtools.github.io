---
title: Plugin FAQ
---

### AEM Tools FAQ

* Plugin suggests Sling Model for completion in *data-sly-use* but in runtime I have error *org.apache.sling.scripting.sightly.render.AbstractRuntimeObjectModel Cannot access method &lt;my method name&gt;*, what am I doing wrong?

<p>
Please make sure that you have correct OSGi directive `Sling-Models-Package` present in sling models containing module. The AEM Tools plugin doesn't take into consideration neither it's presence or correctness.
</p>

<hr/>

* I open HTL file but it seems that it is not recognized by plugin, how do I fix that?

By default *only* html files under *jcr_root* folder are considered as HTL files. You can mark any additional directory as "HTL Root" via context menu *Mark directory as -> HTL Root*

* There are several different plugins with AEM support available for Intellij IDEA, what the difference with AEM Tools, won't it conflict with them?

In general, all the plugins should work well together, here is comparison table for more info:

|Name           |Description        |Is safe to use?|Notes|
| ------------- |:------------------|:--------------|:----|
|[AEM Tools](https://plugins.jetbrains.com/plugin/9397-aem-tools)|General purpose AEM plugin|Y||
|[AEM IDE Tooling4 IntelliJ](https://plugins.jetbrains.com/plugin/9563-aem-ide-tooling-4-intellij)|Server Integration utilities|Y||
|[AEM IntelliJ Plugin](https://plugins.jetbrains.com/plugin/9269-aem-intellij-plugin)|General purpose AEM Plugin|N|It has it own HTL support which may not coexists with AEM Tools|
|[AEM Support](https://plugins.jetbrains.com/plugin/9863-aem-support)|General purpose AEM plugin|Y||
|[IntelliJ Shortcuts For AEM](https://plugins.jetbrains.com/plugin/8639-intellij-shortcuts-for-aem)|Several shortcuts for AEM specific files|Y||
|[IntelliVault](https://plugins.jetbrains.com/plugin/7328-intellivault)|Provides Vault integration|Y||
|[JCR Content Editor](https://plugins.jetbrains.com/plugin/7392-jcr-content-editor)|JCR Utilities|Y||
