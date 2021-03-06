<link rel="stylesheet" href="{{baseUrl}}/css/textbook.css">

<div class="website-content">

<div id="title">

#### What :one:

</div>

<div id="body">

**_Coupling_ is a measure of the degree of _dependence_** between components, classes, methods, etc. Low coupling indicates that a component is less dependent on other components. **High coupling (aka _tight_ coupling or _strong_ coupling) is discouraged** due to the following disadvantages:

* **Maintenance is harder** because a change in one module could cause changes in other modules coupled to it (i.e. a ripple effect).
* **Integration is harder** because multiple components coupled with each other have to be integrated at the same time.
* **Testing and reuse of the module is harder** due to its dependence on other modules.

<tip-box>

:package: In the example below, design `A` appears to have a more coupling between the components than design `B`.

<img src="{{baseUrl}}/designPrinciples/coupling/what/images/playerPuzzleManager.png" height="220" />
<p/>

</tip-box>
</div>
<div id="extras">

<include src="exercises.md" />

</div>

</div>
