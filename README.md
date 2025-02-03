# React Components


![alt text](https://github.com/rog-SARTHAK/React-API-MapLooping/blob/master/01.png)

Looping in JSX:

- We don't have for loops in JSX, so we have to use .map() method of arrays.

```
return (
	<ul>
		{
		students.map((student) => (
			<li key={student}>{student}</li>)
			)
		}
	</ul>
);
```

- React.js will complain if you don't pass key prop to <li>
