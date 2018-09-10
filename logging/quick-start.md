---
description: page description
---

# Quick start

bla bla bla

dfg

{% api-method method="get" host="" path="" %}
{% api-method-summary %}

{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=302 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

$$
a = b
$$

```csharp
public static void MoveOut(Robot robot, int width, int height)
		{
		    while (!robot.Finished)
		    {
		        MoveToNSteps(robot, width - 3, Direction.Right);
		        MoveToNSteps(robot, 2, Direction.Down);
		        MoveToNSteps(robot, width - 3, Direction.Left);
                if (!robot.Finished)
                    MoveToNSteps(robot, 2, Direction.Down);
            }
		}

```

{% file src="../.gitbook/assets/astronaut-on-the-moon-with-bike.jpg" caption="Картинка астронавта" %}



