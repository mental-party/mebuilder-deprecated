# MeBuilder
A Simple Generic Java Object Builder


#### Example
<code>
    
    YourClass newYourClass = GenericBuilder.of(YourClass::new)
        .with(YourClass::setId, 1)
        .build();
        
</code>