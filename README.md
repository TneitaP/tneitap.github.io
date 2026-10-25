This is the sorce code of my homepage https://tneitap.gitee.io/

The homepage starts in dark mode and uses the sun/moon button beside the name to switch between dark and light themes; refreshing the page restores dark mode.

Affiliations groups four roles into two month-based Gantt lanes: Education (light sage green, `#a8d5ba`) and Employment (blue, `#8fc9ff`). Fills stay fixed in both themes; 40px-high bars use white text in dark mode and black text in light mode. Each bar labels the role, institution and city; exact dates remain in accessible `<time datetime="YYYY-MM">` elements. End months are included. The axis spans January of the earliest affiliation year through December of the current year; `Current` extends through the visitor's current month on page load. Small screens can scroll the chart horizontally to keep labels readable. Without JavaScript, roles remain visible as a list.
