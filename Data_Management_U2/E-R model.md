Conceptual data model to describe data. Independent from management and organization of the data. 
____
## Graphical syntax
![[Pasted image 20230602173440.png]]
## Main components
- **Entities** represents classes of objects worthy of autonomous existence.
- An **instance** of an entity is an object of the class that the entity represents. (Ex: Book-> *Inferno*).
- **Attributes** describes properties of interest to the entities, they assume particular values for each instance of the entity. They have cardinalities.
- **Compound attributes** are used for complex aspects. (Address is made of street and house number).
### Relationships
- A **relationship** represent a logical link between two entities. (Example: Person-> *Residence* <- City, Residence is the occurrence of the relationship and is a tuple of dimension 2).
-  A relationship is a subset of the Cartesian product of all the instances of the entities involved, so $rel\subseteq P\times C$.
- A relationship is recursive if it is a relationship between the entity and itself.
- Relationships have attributes.
- Relationship have a cardinality, describing the minimum and maximum number of entity occurrences that can participate.
## Specifics
- An **identifier** is a set of attributes that is different on all instances of its entity (The key).
- An entity can be identified by other entities through a foreign key.
- A generalization is a logical links between two entities, where there is a parent (a super-set) and a child entity. Each instance of the child is also an instance of the parent and it inherits all the attributes.
- A generalization is total if each occurrence of the parent entity is an occurrence of at least one of the child entities, otherwise it is partial. A generalization is exclusive if each occurrence of the parent entity is at most one occurrence of one of the child entities, otherwise it is superimposed (or overlapping).