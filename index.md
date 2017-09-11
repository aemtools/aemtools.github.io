--- 
layout: default 
--- 

### What for?

<p>Development of AEM projects requires dealing with various AEM specific file formats (e.g. HTL), many custom configuration
    files (such as author's dialog definition, security policies etc.). Much burden added to developer's tools set. The goal
    of the project is to make developer's routine work smoother by leveraging abilities IDE may provide.</p>

### Features at glance: 

* HTL Support [image] 
* OSGi [image]
* Specific AEM files support 
  * dialog.xml [Image] 
  * _cq_edit_config.xml [Image] 
  * js.txt & css.txt [Image] 
  
### Changelog [`v0.8.1`](https://github.com/DmytroTroynikov/aemtools/releases/tag/v0.8.1)

##### New features:

<ul id="changelog-accordion" role="tablist">
    <li>
        <a href="https://github.com/DmytroTroynikov/aemtools/issues/115" id="115-heading">
            IDE: make jcr_root directory configurable 
        </a>
        <a href="#115-collapse" data-toggle="collapse" aria-expanded="false">
            <span class="collapse-btn fa fa-arrow-arrow-right">
                show more 
            </span>
        </a>
        <div id="115-collapse" class="collapse hide" data-parent="changelog-accordion" role="tabpanel" aria-labelledby="115-heading">
            <div class="card-block">
                [Image]
            </div>
        </div>
    </li>
    <li>
        <a href="https://github.com/DmytroTroynikov/aemtools/issues/108" id="108-heading">
            HTL: quick fix action for unresolved variable
        </a>
        <a href="#108-collapse" data-toggle="collapse" aria-expanded="false">
            <span class="collapse-btn">
                show more
            </span>
        </a>
        <div id="108-collapse" class="collapse hide" data-parent="changelog-accordion" role="tabpanel" aria-labelledby="108-heading">
            <div class="card-block">
                <video class="col-10" controls src="/assets/images/cnotes/fix_variable.webm">
                </video>
            </div>
        </div>
    </li>
    <li>
        <a href="https://github.com/DmytroTroynikov/aemtools/issues/111">`WIP` HTL: improve completion for i18n expressions</a>
    </li>
</ul>

##### Bug fixes:

<ul>
    <li>
        <a href="https://github.com/DmytroTroynikov/aemtools/issues/117">
            HTL: Disable HTL features in non HTL files
        </a>
    </li>
</ul>

{% include credits.html %}

