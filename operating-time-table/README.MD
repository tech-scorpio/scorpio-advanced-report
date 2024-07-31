# Report description

The report display a table of the operating time of the equipment.

# How to use

The integrator can copy the code and paste it in an advanced report in the advanced report section of the SCorp-io
designer platform.

As the macro contains the @STARTDATE@ and @ENDATE@ strings, the integrator must set the advanced report to display the
date selector and choose a duration.

Before saving the report; the integrator have to modify some constants in the macro code in order to adapt the report to
the building he wants to display the consumption per m2.

The constants are defined at the beginning of the macro tag ( 'macro' <% ) :

```
    /* CONSTANTS TO DEFINE BEGIN SECTION */
    'e04f1312-7fdb-435a-b563-c2635edc96b9' 'projectId' STORE
    'Four n°3 - modèle' 'objectInstanceName' STORE
    'Etat' 'attributeModelName' STORE
    /* CONSTANTS TO DEFINE END SECTION */
```

The integrator have to modify the following constants :

- 'projectId' : the projectId of SCorp-io project
- 'objectInstanceName' : the name of the object instance carrying the operating status
- 'attributeModelName' : the attribute model name of operating status

Enjoy the report !