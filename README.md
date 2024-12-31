
<h1 align="center">Hi 👋, I'm Proyon Das </h1>
<h3 align="center">A Mobile App developer from Bangladesh</h3>
<p align="center">
  <a href="https://www.linkedin.com/in/proyon098/" target="_blank">Linkedin</a> •
  <a href="https://www.facebook.com/proyon098" target="_blank">Facebook</a> •
  <a href="https://twitter.com/proyon098" target="_blank">Twitter</a>
</p>

### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...

```php
<?php

namespace Proyodas;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'WorkFromHome',
                'position' => 'SoftwareDeveloper'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            NodeJs::class,
            ReactNative::class,
            TailwindCss::class,
            Bootstrap::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
