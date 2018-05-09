# bootstrap-fixed-side-navbar
Simple added CSS for bootstrap for fixed-side-navbar

### Examples

#### Left-hand side
    <div class="container-fluid">
      <div class="row">
        <div class="col-sm-3 col-lg-2">
          <nav class="navbar navbar-default navbar-fixed-side">
            <!-- normal collapsible navbar markup -->
          </nav>
        </div>
        <div class="col-sm-9 col-lg-10">
          <!-- your page content -->
        </div>
      </div>
    </div>

#### Right-hand side
Use Bootstrap's [column ordering][co] to maintain source order

    <div class="container-fluid">
      <div class="row">
        <div class="col-sm-3 col-lg-2 col-sm-push-9 col-lg-push-10">
          <nav class="navbar navbar-default navbar-fixed-side">
            <!-- normal collapsable navbar markup -->
          </nav>
        </div>
        <div class="col-sm-9 col-lg-10 col-sm-pull-3 col-lg-pull-2">
          <!-- your page content -->
        </div>
      </div>
    </div>

### Options

The side navbar supports the inverse style for navbars. Replace `.navbar-default` with `.navbar-inverse` as normal.

[co]: https://getbootstrap.com/css/#grid-column-ordering
[nft]: http://getbootstrap.com/components/#navbar-fixed-top
