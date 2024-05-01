# fy

```python
class Area():
    def __init__(self, x, y, width, height, color=YELLOW):
        self.rect = pygame.Rect(x, y, width, height)
        self.fill_color = color
    def fill(self):
        pygame.draw.rect(window, self.fill_color, self.rect)
        # pygame.draw.rect(window, BLUE, self.rect, 3)
    def color(self, new_color):
        self.fill_color = new_color
    def collidepoint(self, x, y):
        return self.rect.collidepoint(x, y)



```
