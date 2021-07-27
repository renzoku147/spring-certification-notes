# Section 1-1 – Container, Dependency and IOC

• What is dependency injection and what are the advantages of using it?
DI es el proceso en el cual un servicio externo, por ejemplo un framework, establece las interelaciones entre partes de la aplicacion/ estable las dependencias entre clases.
Reduce el acoplamiento.
Aumenta la mantenibilidad (los cambios se hacen en los bean dependiendo de la necesidad)
Promueve el uso de interfaces.


• What is an interface and what are the advantages of making use of them in Java?
Interface, es un tipo abstracto, como una clase que define un comportamiento que pueden metodos sin cuerpo que debe ser implentado por una clase.
Reduce el acoplamiento, las clases no dependen de una entidad concreta


• What is an ApplicationContext?
Es una enviroment que gestiona los beans (ciclo de vida de los beans)
Se inicia con una configuracion que puede ser XML o Java based
Se encarga de inicializar todos los beans antes de su primer uso
Establece las dependencias entre bean en el orden como son declarados (corregir)


• How are you going to create a new instance of an ApplicationContext?

• Can you describe the lifecycle of a Spring Bean in an ApplicationContext?

• How are you going to create an ApplicationContext in an integration test?

• What is the preferred way to close an application context? Does Spring Boot do this for you?

• Are beans lazily or eagerly instantiated by default? How do you alter this behavior?

• What is a property source? How would you use @PropertySource?

• What is a BeanFactoryPostProcessor and what is it used for? When is it invoked?

• What is a BeanPostProcessor and how is it different to a BeanFactoryPostProcessor? What do they do? When are they called?

• What does component-scanning do?

• What is the behavior of the annotation @Autowired with regards to field injection, constructor injection and method injection?

• How does the @Qualifier annotation complement the use of @Autowired?

• What is a proxy object and what are the two different types of proxies Spring can create?

• What does the @Bean annotation do?

• What is the default bean id if you only use @Bean? How can you override this?

• Why are you not allowed to annotate a final class with @Configuration

• How do you configure profiles? What are possible use cases where they might be useful?

• Can you use @Bean together with @Profile?

• Can you use @Component together with @Profile?

• How many profiles can you have?

• How do you inject scalar/literal values into Spring beans?

• What is Spring Expression Language (SpEL for short)?

• What is the Environment abstraction in Spring?

• Where can properties in the environment come from – there are many sources for properties – check the documentation if not sure. Spring Boot adds even more.

• What can you reference using SpEL?

• What is the difference between $ and # in @Value expressions?
