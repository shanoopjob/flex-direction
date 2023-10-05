# flex-direction

.parent or container
{
display:flex;
or
display: inline-flex; /*Only take the space of the content; you can see the difference with setting a border*/
 flex-direction: column or row;
 }
 .child
 {
  flex-basis: 100px; /*It act as height when flex direction: is column and width as flex-direction: row , effects only take if it is a flexible item(means parent must be flex); */
 }
