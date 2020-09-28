
## Bacic ANNOTATIONS

| ANNOTATIONS                      |Use                        |
|-------------------------------|----------------|
|@Entity	|use to mark any class as Entity    |        
|@Table         |use to change the table details            |
|@Id        |use to mark column as id(primary key)|
|@GeneratedValue    |Hibernate will automatically generate values for that an internal sequence. Therefore we don't have to set it manually|
|@Column      |Can be used to specify column mapping. For example, to change the column name is the associated table in datatbse.|
|@Transient	|This tells hibernate not to save this field|
|@Temporal  |@Temporal over the date field tells hibernate the format in which the date need to be saved|
|@Lob       |@Lob is used to for large Object|
|

@OneToOne, @OneToMany, @ManyToMany, @ManyToOne, @JoinColumn etc.

