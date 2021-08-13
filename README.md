# Bootstrap Drawer

Drawer allows you to display additional content within the boundaries of a given component (for example navigation links), by default invisible and displayed after clicking the trigger.

Drawers are commonly referred to as a Side Nav or Offcanvas navigation.

## Basic example

```html
<!-- Sidenav -->
<nav
  id="sidenav-1"
  class="sidenav"
  data-mdb-hidden="false"
>
  <ul class="sidenav-menu">
    <li class="sidenav-item">
      <a class="sidenav-link">
        <i class="far fa-smile fa-fw me-3"></i><span>Link 1</span></a
      >
    </li>
    <li class="sidenav-item">
      <a class="sidenav-link"
        ><i class="fas fa-grin fa-fw me-3"></i><span>Category 1</span></a
      >
      <ul class="sidenav-collapse show">
        <li class="sidenav-item">
          <a class="sidenav-link">Link 2</a>
        </li>
        <li class="sidenav-item">
          <a class="sidenav-link">Link 3</a>
        </li>
      </ul>
    </li>
    <li class="sidenav-item">
      <a class="sidenav-link"
        ><i class="fas fa-grin-wink fa-fw me-3"></i><span>Category 2</span></a
      >
      <ul class="sidenav-collapse">
        <li class="sidenav-item">
          <a class="sidenav-link">Link 4</a>
        </li>
        <li class="sidenav-item">
          <a class="sidenav-link"
            >Link 5</a
          >
        </li>
      </ul>
    </li>
  </ul>
</nav>
<!-- Sidenav -->

<!-- Toggler -->
<button
  data-mdb-toggle="sidenav"
  data-mdb-target="#sidenav-1"
  class="btn btn-primary"
  aria-controls="#sidenav-1"
  aria-haspopup="true"
>
  <i class="fas fa-bars"></i>
</button>
<!-- Toggler -->
```

#### Much more examples and a detailed description can be found at [📄 Drawer documentation page](https://mdbootstrap.com/docs/standard/extended/drawer/)



