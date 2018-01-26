# java-language-constraints

This project try to describe the advantages and the constraints of the java language.

# constraints

[can not get all variables in scope](https://stackoverflow.com/questions/12659117/how-do-i-list-all-local-variables-within-a-java-method-function)

you cant create generic arrays like this:

´´´

	public static <T> T[] toArray(final List<T> elements)
	{
		final T[] decorator =elements.toArray(new T[elements.size()]);
		return decorator;
	}  

´´´
