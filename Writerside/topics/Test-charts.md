# Test charts

<var name="v1" value="1.0"/>
<var name="v2" value="2.0"/>

<code-block lang="plantuml">
    @startuml
    [Component] --> "Interface %v1%"
    [Component] --> "Interface %v2%"
    @enduml
</code-block>

## Sequence diagram

<code-block lang="plantuml">
    @startuml
    participant Participant as Foo
    actor       Actor       as Foo1
    boundary    Boundary    as Foo2
    control     Control     as Foo3
    entity      Entity      as Foo4
    database    Database    as Foo5
    collections Collections as Foo6
    queue       Queue       as Foo7
    Foo -> Foo1 : To actor 
    Foo -> Foo2 : To boundary
    Foo -> Foo3 : To control
    Foo -> Foo4 : To entity
    Foo -> Foo5 : To database
    Foo -> Foo6 : To collections
    Foo -> Foo7: To queue
    @enduml
</code-block>
