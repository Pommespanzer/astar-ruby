# A* (Astar)
See:    http://en.wikipedia.org/wiki/A*_search_algorithm
Author: Markus Handschuh <yuri.designs@googlemail.com>

# How to use
`start       = { 'x' => MY_X, 'y' => MY_X }
destination = { 'x' => MY_X, 'y' => MY_Y }
pathfinder  = Astar.new(start, destination)
result      = astar.search # returns Array

if (result.size > 0)
  result.each{|node| # Astar_Node
    # your code ...
  }
end`

See method passable

# License
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
Version 2, December 2004

Copyright (C) 2004 Sam Hocevar
14 rue de Plaisance, 75014 Paris, France
Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.

                   DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

0. You just DO WHAT THE FUCK YOU WANT TO.