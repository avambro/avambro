### Hi there 👋



```php
<?php

namespace Mode\Developer;

class About extends Me
{
    

    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Insurance Services',
                'position' => 'Software Architect'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            PHP,
            Typescript,            
            VueJs,
            NodeJs,
            AWS,
            Python,
            Cybersecurity,
            Team_Lead,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```

