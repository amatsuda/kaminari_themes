## Pagination for [Codyhouse -1](codyhouse.co/demo/pagination/index.html)

With support for:

- erb

###stylesheet 
you will need to add this css also 

```css
nav[role="codyhouse"] {
  text-align: center;
}

.cd-pagination {
  width: 90%;
  max-width: 768px;
  margin: 2em auto 4em;
  text-align: center;
}
.cd-pagination li {
  /* hide numbers on small devices */
  display: none;
  margin: 0 .2em;
}
.cd-pagination li.button {
  /* make sure prev next buttons are visible */
  display: inline-block;
}
.cd-pagination a, .cd-pagination span {
  display: inline-block;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* use padding and font-size to change buttons size */
  padding: .6em .8em;
  font-size: 1.6rem;
}
.cd-pagination a {
  border: 1px solid #e6e6e6;
  border-radius: 0.25em;
}
.no-touch .cd-pagination a:hover {
  background-color: #f2f2f2;
}
.cd-pagination a:active {
  /* click effect */
  -webkit-transform: scale(0.9);
  -moz-transform: scale(0.9);
  -ms-transform: scale(0.9);
  -o-transform: scale(0.9);
  transform: scale(0.9);
}
.cd-pagination a.disabled {
  /* button disabled */
  color: rgba(46, 64, 87, 0.4);
  pointer-events: none;
}
.cd-pagination a.disabled::before, .cd-pagination a.disabled::after {
  opacity: .4;
}
.cd-pagination .button:first-of-type a::before {
  content: '\00ab  ';
}
.cd-pagination .button:last-of-type a::after {
  content: ' \00bb';
}
.cd-pagination .current {
  /* selected number */
  background-color: #64a281;
  border-color: #64a281;
  color: #ffffff;
  pointer-events: none;
}
@media only screen and (min-width: 768px) {
  .cd-pagination li {
    display: inline-block;
  }
}
@media only screen and (min-width: 1170px) {
  .cd-pagination {
    margin: 1em auto .1em;
    //margin: 4em auto 8em;
  }
}



```