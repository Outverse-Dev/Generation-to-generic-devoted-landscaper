# Documentation.

This is the official documentation for how most tools inside G2GDL work.

## Objects and Blocks
  ## Objects
  An object is a physical space that accompanies part of the dimension that it is in.

  Object can be created with:
    obj = obj.new()

  Configuring objects is also easy!
    To alter its square do:
      obj(x=1, y=-1)
    To change the size do:
      obj(h=9, w=4)

  ## Blocks
  A block is a non-physical area used to simulate an attack box also known as a hitbox.
  A hitbox is drawn around the character by default and cannot be configured.
  You can draw hitboxes by doing:
    hit = hitbox.draw( )
Configuring said hitbox is rather simple as to change sizes and positions you have to do the same as with Objects.
