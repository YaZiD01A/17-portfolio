/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

This is a regex that verifies the Hex value. ^ is an anchor. it indicate that the expression must start with a #. ? makes the preceding character optional. [a-f0-9]{6}|[a-f0-9]{3} means the specified characters are required to repeat by the number specified like six and three.| is an or operator so both expressions are allowed.

Author: Yazid Alhujery

Github: https://github.com/YaZiD01A