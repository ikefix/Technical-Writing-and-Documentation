---
title: "Introduction to JavaScript Destructuring"
datePublished: Thu Aug 24 2023 11:43:03 GMT+0000 (Coordinated Universal Time)
cuid: cllp3hgwz000o08mld0091d0b
slug: introduction-to-javascript-destructuring
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1692858428722/2c54fcce-0978-4cc9-ade1-e81559b50bc0.jpeg

---

**1\. OVERVIEW**:

In this tutorial, we‘ll introduce and discuss JavaScript Destructuring in a code-focused and practical manner.

We'll discuss destructuring in the array after which we will proceed to object destructuring.

We explain several ways we can destructure arrays and objects.

We explain how we can use array destructuring to; **extract value at any Index, Assign the Rest of an Array to a Variable, Swap variables, Extract values from array to a Function.**

We also discuss how we can use object destructuring in; **Assigning a new variable name, combining array and objects, Applying Rest to Object Destructuring and, Applying nesting to object.**

**2\. Why Destructuring?**

Destructuring is a JavaScript expression that allows us to extract data from arrays, objects, and maps and set them into new, distinct variables. Destructuring is a feature that comes along with ES6 features. Destructuring allows us to extract multiple properties or items from an array at a time. It makes it easier to extract only what is needed.

Previously when we wanted to extract data from an array, we had to repeat the same thing over and over again. Since the immerge of Es6 JavaScript Destructuring, extracting data has to be easier.

It’s called a “destructuring assignment,” because it “destructurizes” by copying items into variables.

Here is the old way we extract data from an Array:

![Old way of extracting data from an Array](https://cdn.hashnode.com/res/hashnode/image/upload/v1691260429876/6db76e84-ec07-434c-bf18-69c96e732658.jpeg align="left")

From the code snippet, we can see that when we want to extract data from an array we have to repeat the same thing over and over again.

**3\. Array Destructuring**

From our previous example instead of going through those repetitive processes, we'll introduce the Es6 destructuring assignment to extract data from an array

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1691320327245/e1bb6e06-1a75-43ba-9c91-aeca14ebc061.jpeg align="left")

This can be done like this as well:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1691322264413/7f83b306-ebfd-430c-83d5-4a346f5f8af5.jpeg align="left")

**3.1. Using Array destructuring to extract value at any Index**

Array destructuring can be used to extract value at any index position of an array. If for instance, we want to get the first and last item on our array of data, we can use array destructuring.

We use the comma to skip values in an array, so if we want to skip items in an array we use the comma

Here is an example below:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1691336340674/b78c7264-b7ae-4322-bf63-500fd29f6014.jpeg align="left")

**3.2.** **Using Array Destructuring to Assign the Rest of an Array to a Variable**

We'll use the [rest operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters) in our array to assign the rest of the array to a variable. The rest operator is written using three dots (...).

Every javascript programmer should be familiar with the rest operator because it makes our code cleaner and easier to read, It also aids in quick and easy manipulation of collections and arguments.

Here is an example below:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1691765131029/947b8761-edc7-4ff0-b353-9181b894da47.jpeg align="left")

**3.3. Swapping variables using array destructuring**

We'll use array destructuring to swap two or more different variables. With this, swapping variables will be easier.

Here is an example where we swap two variables:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1691768583810/0e56e4b2-cdef-4f05-bb16-503111e5e08c.jpeg align="left")

**3.4. Extracting values from an array to a Function using array destructuring**

we'll extract value from an array to a function here.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1692771653540/2045dac2-ba92-48fe-a80c-a6d5ef6cbb17.png align="left")

**4\. Object Destructuring**

Object destructuring is a JavaScript feature in JavaScript that allows us to extract properties from objects and assign them to variables.

**4.1. Basic Object Destructuring**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1692804427742/27298675-f7be-4c15-a311-8e2b11291633.png align="left")

From the code snippet above we assign an object’s value to a variable when both the object’s property and the variable have the same name.

The code defines an object myData with several properties and then it uses object destructuring to extract values from myData

**4.2. Assigning a new variable name**

with JavaScript we can use object destructuring to extract a property's value into a variable that is different from the variable name.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1692828510518/5f290535-1f5a-4725-937c-3389af2ce666.png align="left")

**4.3. Using array and objects**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1692834591772/77b91f27-7a88-48d9-8834-57fb0d9ad958.png align="left")

**4.4. Applying Rest in Object Destructuring**

We will use object destructuring to assign the rest of an object in the given variable.

The rest operator (...) was used to take the remaining data. (...otherData)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1692860566878/32677f7d-e4ec-4a2c-b9fb-32d4c6c483c3.png align="left")

**4.5. Applying nesting in object destructuring**

We can also nest objects in destructuring.

Below is a nested object myData

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1692874082211/72706202-eae6-436a-acaf-7e4309c4275c.png align="center")

**5\. Conclusion**

In this article, we have discussed how to apply JavaScript destructuring. We discuss various ways we can destructure arrays and objects. We can apply destructuring in building a lot of things.