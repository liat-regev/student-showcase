# How to Sort Your Laundry
> **_NOTE:_**  For simplicity's sake, the following flowchart assumes your laundry contains only clothing items. Towels, bedding, and other laundry items are excluded from this flowchart.

```mermaid
graph TD;
A([Start])-->B[Go to laundry hamper]
style A fill:#52BD94, stroke:#52BD94
style B fill:#FFFFFF, stroke:#292F36,stroke-width:2px

B-->C{Does the hamper contain </br> any laundry items?}
style C fill:#D6E0FF, stroke:#D6E0FF

C-->|Yes| D[Pick a clothing item]
style D fill:#FFFFFF, stroke:#292F36,stroke-width:2px

C-->|No| E([End])
style E fill:#52BD94, stroke:#52BD94

D-->F{Is it </br> delicate?}
style D fill:#FFFFFF, stroke:#292F36,stroke-width:2px
style F fill:#D6E0FF, stroke:#D6E0FF

F-->|Yes| G{Is it </br> dark-colored?}
style G fill:#D6E0FF, stroke:#D6E0FF
G-->|Yes| H[Put in a pile for dark-colored delicates]
G-->|No| I[Put in a pile for light-colored delicates]
style H fill:#FFFFFF, stroke:#292F36,stroke-width:2px
style I fill:#FFFFFF, stroke:#292F36,stroke-width:2px

F-->|No| J{Is it </br> dark-colored?}
style J fill:#D6E0FF, stroke:#D6E0FF
J-->|Yes| K[Put in a pile for dark-colored regular garments]
J-->|No| L[Put in a pile for light-colored regular garments]
style K fill:#FFFFFF, stroke:#292F36,stroke-width:2px
style L fill:#FFFFFF, stroke:#292F36,stroke-width:2px

```





