# Report description

The report display a bar chart of the top defaults of the project.
The report count the occurrences of truthy values for TA attributes between the start and the end date of the report.

# How to use

The integrator can copy the code and paste it in an advanced report in the advanced report section of the SCorp-io
designer platform.
Before saving the report; the integrator have to modify some constants in the macro code in order to adapt the report to
the project he wants to display the top x default.

The constants are defined at the beginning of the macro tag ( 'macro' <% ) :

```
    /* CONSTANTS TO DEFINE BEGIN SECTION */
    5 'nbDefaults' STORE
    'de314c5c-e2cc-4a84-8904-0251aaf14c04' 'projectId' STORE
    /* CONSTANTS TO DEFINE END SECTION */
```

The integrator have to modify the following constants :

- 'projectId' : the projectId of SCorp-io project
- 'nbDefaults' : the number of defaults to display in the report

Enjoy the report !