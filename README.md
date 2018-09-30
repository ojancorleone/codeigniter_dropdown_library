# codeigniter_dropdown_library

Library for initiation dropdown html (select box) in codeigniter based on query..



Installation  :
1. Save Drop_down.php inside library folder Codeigniter
2. Load library  $this->load->library("drop_down");

How To Use (simplify):

$this->drop_down->select(YOUR_ID, YOUR_ANOTHER_COLUMN);

$this->drop_down->from(YOUR_TABLE);

$dropdown = $this->drop_down->build();


#NOTE : Echo inside select tag html in Your view file


Method List :

1. Select
2. From
3. Where
4. Order




