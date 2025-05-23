@brief      ESP Debug Workspace
@details    x
@auth       Justin Reina
@date       5/23/25


@section    Setup
    
    @pre    setup 'r1' from Installation Guide [1]
        
    @targ   esp32-s3
    
    @task   identify compile issues with new work
    
@section    Test Projects
    
    base - 'hello_world', 'blink'
    
    freertos - 'real_time_stats'
    
    bt - 'Bluedroid_Beacon'
    
    wifi - 'scan'
    
    custom - 'esp32_gpio' [2]
             'esp32_rtos' [3]
             
@section    Test Procedure

    Project -> Clean...
    
    Project -> Build Project

@section    Reference
    1. https://jmreina.atlassian.net/wiki/spaces/~5d7d25788ce6b60c381129f0/pages/73269283/Setup+Procedure

    2. https://github.com/ErisdarDemo/esp32_gpio (#publ)

    3. https://github.com/ErisdarDemo/esp32_rtos (#publ)

