# Voronoi_wb_on_ghPython  


ghpythonlib.components as ghpc で、アドオンも呼び出せるっぽい。  
WeaverBird は確認済み。  



```python
import ghpythonlib.components as ghpc



### WeaverBird Mesh
picture_ = ghpc.WeaverBird.WeaverbirdsPictureFrame(cell_, 30, 0)
thicken_ = ghpc.WeaverBird.WeaverbirdsMeshThicken(picture_, 0.25, 0)
loop_sub_ = ghpc.WeaverBird.WeaverbirdsLoopSubdivision(thicken_, 3, 1)

```