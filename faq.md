---
title: Plugin FAQ
---

AEM Tools FAQ

* Plugin suggests Sling Model for completion in `data-sly-use` but in runtime I have error `org.apache.sling.scripting.sightly.render.AbstractRuntimeObjectModel Cannot access method <name>`, what am I doing wrong?

<p>
Please make sure that you have correct OSGi directive `Sling-Models-Package` present in sling models containing module. The AEM Tools plugin doesn't take into consideration neither it's presence or correctness.
</p>

<hr/>

* I open HTL file but it seems that it is not recognized by plugin, how do I fix that?

By default *only* html files under *jcr_root* folder are considered as HTL files. You can mark any additional directory as "HTL Root" via context menu `Mark directory as -> HTL Root` (not yet released subject of `v0.8.1`, beta available by this [link](https://github.com/DmytroTroynikov/aemtools/releases/tag/v0.8.1-beta1))



