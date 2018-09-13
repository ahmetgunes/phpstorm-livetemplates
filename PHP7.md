#### ate
###### Adds an attribute template to the entity

```php
    /**
     * @var string
     *
     * @ORM\Column(name="", type="")
     */
    protected $$$END$;

```



#### ats
###### Adds an attribute template to the entity

```php
    /**
     * @var string
     *
     * @ORM\Column(name="", type="string", length="")
     */
    protected $$$END$;

```

#### ati
###### Adds an integer attribute to the entity

```php

    /**
     * @var int
     *
     * @ORM\Column(name="", type="int")
     */
    protected $$$END$;
```


#### actf
###### Adds a generic Symfony2 "Action" to the controller

```php

    /**
     * @param Request $request
     * @return array
     * @Route("/", name="")
     * @Template("")
     */
    public function $END$Action(Request $request)
    {
        return [];
    }
```
