# Kanban

Kanban is an approach to software development in which teams focus on continuous delivery to customers. It implements an agile life-cycle, which applies to situations in which teams need to react to ever changing demands from customers. 

## Kanban's Roots
![Toyota Kanban](/images/toyota_kanban.jpg?raw=true "Toyota Kanban")

Kanban was developed by Toyota in 1953 as a production technique to meet the ever changing demand for its products. A research team studied how supermarkets implemented a product similar production technique to efficiently stocked their shelves. The team realized that the supermarkets would stock only the supply of items that they expected customers would demand at a given time. For example, when the demand for a product decreased, the supermarket would reduce the supply of that product. Previously, supermarkets would keep a fixed stock of all of their products. However, this was innefficient as the supermarket could not react to change. 

Toyota applied this technique to its production floor. Let's image a production crew consisting of three teams: A, B, and C. Team A feeds its work to B and B feeds its work to C. If team B becomes overwhelmed with work, Kanban enables team A to stop production and focus on another task. Because team C now sees a decrease in incoming work, Kanban enables C to also focus its attention on another task. When team B is back on track, teams A and C can go back to their their original tasks. 

This style of production allows for products to leave the facility in a continuous stream. A given team is never ide, waiting for another team to finish its work. If a bottleneck occurs during one part of the production cycle, resources are refocused to other tasks, ensuring continuous production.

## Kanban Software Development

To help monitor the progress of a software project, some development teams use a "Kanban board", such as that shown in the figure below. The Kanban board enables developers in agile life-cycles to continuously monitor user stories and issues as they pass through different phases of development, analogous to the Toyota assembly line. The Kanban board is usually a physical board with tasks written on individual pieces of paper, as the figure below shows:
![Typical Kanban Board](/images/kanban_board.jpg?raw=true "Typical Kanban Board")
- When a team has decided to add a story, it writes it down on paper and posts it in the "To Do" column.
- When the team is ready to work on the story, it moves its paper to the "Doing" column.
- When the team is finished with the story, it moves its paper to the "Done" column.

This allows teams to continuously track the progress of stories and issues throughout the software development life-cycle.

Waffle is an online software focused around Kanban development life-cycles. It acts as a dynamic Kanban board, where users can add and move issues throughout the system. Waffle's Kanban board allows developers to easily track their progress with GitHub integration and simple to use UI. This makes it easy for experienced GitHub users to adopt this tool into their development processes.

Up Next: [Set-Up](https://github.com/rpcrimi/WaffleIO/blob/master/markdown/set_up.md)


















