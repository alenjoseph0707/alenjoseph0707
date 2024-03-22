<?php

namespace AlenJoseph;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Phases',
                'position' => 'SoftwareEngineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Python::class
            Javascript::class,
            Wordpress::class,
            Drupal::class,
           
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
