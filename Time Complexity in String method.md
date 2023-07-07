# Time Complexity in String Method
1. `charAt(int index)`: O(1)
2. `codePointAt(int index)`: O(1)
3. `codePointBefore(int index)`: O(1)
4. `codePointCount(int beginIndex, int endIndex)`: O(endIndex - beginIndex)
5. `compareTo(String anotherString)`: O(n), where n is the length of the longer string
6. `compareToIgnoreCase(String str)`: O(n), where n is the length of the longer string
7. `concat(String str)`: O(m), where m is the length of the concatenated string
8. `contains(CharSequence sequence)`: O(n*m), where n is the length of the string and m is the length of the sequence
9. `contentEquals(CharSequence cs)`: O(n), where n is the length of the string
10. `contentEquals(StringBuffer sb)`: O(n), where n is the length of the string
11. `endsWith(String suffix)`: O(m), where m is the length of the suffix
12. `equals(Object anObject)`: O(n), where n is the length of the longer string
13. `equalsIgnoreCase(String anotherString)`: O(n), where n is the length of the longer string
14. `format(String format, Object... args)`: O(n), where n is the length of the formatted string
15. `getBytes()`: O(n), where n is the length of the string
16. `getBytes(Charset charset)`: O(n), where n is the length of the string
17. `getBytes(String charsetName)`: O(n), where n is the length of the string
18. `hashCode()`: O(n), where n is the length of the string
19. `indexOf(int ch)`: O(n), where n is the length of the string
20. `indexOf(int ch, int fromIndex)`: O(n), where n is the length of the string
21. `indexOf(String str)`: O(n*m), where n is the length of the string and m is the length of the substring
22. `indexOf(String str, int fromIndex)`: O(n*m), where n is the length of the string and m is the length of the substring
23. `intern()`: O(1)
24. `isEmpty()`: O(1)
25. `lastIndexOf(int ch)`: O(n), where n is the length of the string
26. `lastIndexOf(int ch, int fromIndex)`: O(n), where n is the length of the string
27. `lastIndexOf(String str)`: O(n*m), where n is the length of the string and m is the length of the substring
28. `lastIndexOf(String str, int fromIndex)`: O(n*m), where n is the length of the string and m is the length of the substring
29. `length()`: O(1)
30. `matches(String regex)`: O(n), where n is the length of the string
31. `offsetByCodePoints(int index, int codePointOffset)`: O(1)
32. `regionMatches(boolean ignoreCase, int toffset, String other, int ooffset, int len)`: O(len), where len is the length of the substring being compared
33. `regionMatches(int toffset, String other, int ooffset, int len)`: O(len), where len is the length of the substring being compared
34. `replace(char oldChar, char newChar)`: O(n), where n is the length of the string
35.Apologies, I made a mistake in the previous response. The correct time complexities for the remaining string methods are:
35. `replace(CharSequence target, CharSequence replacement)`: O(n*m), where n is the length of the string and m is the length of the target CharSequence
36. `replaceAll(String regex, String replacement)`: O(n*m), where n is the length of the string and m is the length of the replacement string
37. `replaceFirst(String regex, String replacement)`: O(n*m), where n is the length of the string and m is the length of the replacement string
38. `split(String regex)`: O(n), where n is the length of the string
39. `split(String regex, int limit)`: O(n), where n is the length of the string
40. `startsWith(String prefix)`: O(m), where m is the length of the prefix
41. `startsWith(String prefix, int toffset)`: O(m), where m is the length of the prefix
42. `subSequence(int beginIndex, int endIndex)`: O(endIndex - beginIndex)
43. `substring(int beginIndex)`: O(n), where n is the length of the string
44. `substring(int beginIndex, int endIndex)`: O(n), where n is the length of the string
45. `toCharArray()`: O(n), where n is the length of the string
46. `toLowerCase()`: O(n), where n is the length of the string
47. `toLowerCase(Locale locale)`: O(n), where n is the length of the string
48. `toString()`: O(n), where n is the length of the string
49. `toUpperCase()`: O(n), where n is the length of the string
50. `toUpperCase(Locale locale)`: O(n), where n is the length of the string
51. `trim()`: O(n), where n is the length of the string