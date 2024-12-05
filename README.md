# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug where `useEffect` causes an infinite render loop. The bug is caused by the effect running after every render without specifying any dependencies, leading to an infinite loop.  The solution shows how to fix this by correctly specifying dependencies to only trigger the effect when the needed values change. 