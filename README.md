```php
public function aboutMe()
{
    $name = "Hadziq";
    $pronouns = ["he", "him"];
    $profession = "Backend Developer";
    $preferredTechStack = ["php", "laravel"];
    
    return view('aboutme', compact('name', 'pronouns', 'profession', 'preferredTechStack'));
}
```
