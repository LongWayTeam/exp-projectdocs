# Test charts

<var name="v1" value="1.0"/>
<var name="v2" value="2.0"/>

<code-block lang="plantuml">
    @startuml
    [Component] --> "Interface %v1%"
    [Component] --> "Interface %v2%"
    @enduml
</code-block>

[//]: # (<code-block lang="plantuml">)

[//]: # (@startuml)

[//]: # (User-visit -> Login page)

[//]: # (User-enter a username/password -> Login page)

[//]: # (User-login -> Login page)

[//]: # (Login page-send username/password hash -> Database)

[//]: # (Database-validate user login data -> Database)

[//]: # (/alt Login data is correct)

[//]: # (    Database-. user login accepted->+ Login page)

[//]: # (    Login page- redirect→Login page)

[//]: # (    Login page-. Successfull login &#40;message&#41; ->User)

[//]: # (/else Login data is incorrect)

[//]: # (Database. user login rejected->+ Login page)

[//]: # (Login page- redirect -> Login page)

[//]: # (Login page-. clear the password field for the new entry -> User)

[//]: # (@enduml)

[//]: # (</code-block>)