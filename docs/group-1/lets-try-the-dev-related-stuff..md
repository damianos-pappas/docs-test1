# Let's try the dev related stuff.

```csharp
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```

The c# code looks awesome!!!!!

<details>

<summary>Exception example expandable here</summary>

System.ApplicationException: Error during execute ---> System.FormatException: Input string was not in a correct format.   at System.Number.ThrowOverflowOrFormatException(ParsingStatus status, TypeCode type)   at System.Number.ParseInt32(ReadOnlySpan\`1 value, NumberStyles styles, NumberFormatInfo info)   at System.Int32.Parse(String s)   at MyNamespace.IntParser.Execute(String s) in C:\apps\MyNamespace\IntParser.cs:line 13   --- End of inner exception stack trace ---   at MyNamespace.IntParser.Execute(String s) in C:\apps\MyNamespace\IntParser.cs:line 17   at MyNamespace.Program.Main(String\[] args) in C:\apps\MyNamespace\Program.cs:line 13





</details>

{% swagger src="https://petstore.swagger.io/v2/swagger.json" path="/pet/{petId}/uploadImage" method="post" %}
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)
{% endswagger %}

{% swagger src="https://petstore.swagger.io/v2/swagger.json" path="/pet" method="post" %}
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)
{% endswagger %}

{% swagger src="https://petstore.swagger.io/v2/swagger.json" path="/pet" method="put" %}
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)
{% endswagger %}

{% swagger src="https://petstore.swagger.io/v2/swagger.json" path="/pet/{petId}" method="get" %}
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)
{% endswagger %}

{% swagger src="https://petstore.swagger.io/v2/swagger.json" path="/pet/{petId}" method="post" %}
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)
{% endswagger %}

openapi endpoints right in the documentation........!!!!

{% swagger method="get" path="" baseUrl="" summary="" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}

{% swagger method="get" path="" baseUrl="https://petstore3.swagger.io/api/v3/store/inventory" summary="This brings some petstores, just a get call, right throgh the docs" %}
{% swagger-description %}
I don't know what it really fetches, some dummy data probably, but... perfect for the poc
{% endswagger-description %}
{% endswagger %}

{% tabs %}
{% tab title="First Tab" %}
oh we also have tabs
{% endtab %}

{% tab title="Second Tab" %}
nice pretty tabs
{% endtab %}

{% tab title="Untitled" %}
and another one
{% endtab %}
{% endtabs %}

{% embed url="https://www.youtube.com/watch?v=OJjVvPINlYA" %}

{% hint style="info" %}
Here is a hint: hints are good
{% endhint %}

<img src="../.gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

