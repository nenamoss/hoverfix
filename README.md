hoverfix
========

When you mouse over a link, you often see a "tooltip" — a "hover box" with information about the item being hovered over. This effect is achieved via the title attribute for a link. Unfortunately, the title attribute isn't consistently accessed by search engines, screen readers, or by keyboard functions (tabbing). Many users can't read this information.

Do not dismay! There is an accessible way to provide this extra information about a link. It uses the CSS span tag behind the scenes, but acts like a tooltip or mousehover. When the element comes into focus, the information is displayed. Text in the span tag is read by screen readers and easily accessed by tabbing (for those who can't use a mouse).
