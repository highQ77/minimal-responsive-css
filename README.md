# minial-responsive-css
Minimal Flex-Based Responsive CSS Layout System

Design by William77
#### You can use it in any projects (include commercial usage)

Demo : https://github.com/highQ77/minial-responsive-css
 

### all class you need to know
 * su-row
 * su-col-sm-1 ~ su-col-sm-12
 * su-col-md-1 ~ su-col-md-12
 * su-col-lg-1 ~ su-col-lg-12
 * row-bound

#### example 1

```
  <div class='su-row'>
    <div>A</div>
    <div>B</div>
    <div>C</div>
  </div>
```

#### example 2

```
  <div class='su-row'>
    <div class="su-col-sm-6 su-col-md-6 su-col-lg-4">
      <div class='su-row'>
        <div class="su-col-sm-12 su-col-md-6 su-col-lg-6">D</div>
        <div class="su-col-sm-12 su-col-md-6 su-col-lg-6">E</div>
      </div>
    </div>
    <div class="su-col-sm-6 su-col-md-6 su-col-lg-4">F</div>
    <div class="su-col-sm-12 su-col-md-6 su-col-lg-4">G</div>
  </div>
```

#### example 3

```
  <div class='su-row row-bound'>
    <div>A</div>
    <div>B</div>
    <div class="su-col-sm-12 su-col-md-6 su-col-lg-4">C</div>
  </div> 
```

#### example 4

```
<div class='su-row su-row-bound'>
    <div style="height: 100px;">no align box</div>
    <div class="su-align-box su-align-top">top</div>
    <div class="su-align-box su-align-middle">middle</div>
    <div class="su-align-box su-align-bottom">bottom</div>
    <div class="su-align-box su-align-left">left</div>
    <div class="su-align-box su-align-center">center</div>
    <div class="su-align-box su-align-right">right</div>
    <div class="su-align-box su-align-middle su-align-center">middle & center</div>
</div>
```