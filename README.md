### Hi Baby 👋

![](https://visitor-badge.glitch.me/badge?page_id=wizwizdev.wizwizdev)

```php
<?php
namespace AshBaker;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Nita',
                'position' => 'Founder'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            my::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
