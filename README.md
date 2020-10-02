# Teamify

teamify - Given a list of students, generate random teams. Intended to be used as a filter, so provide input via a pipe or file

```bash
teamify [-n size] <somefile.txt
```

As written, the last team contains student_count % team_size members, so you may want to manually redistribute the members assigned to this team.

## Example

```bash
sean@MANPUTER:~/projects/teamify$ ./teamify -n10 < names.txt
Team 1:
👑 Samuel Chase
Lyman Hall
Abraham Clark
Benjamin Rush
Oliver Wolcott
Francis Lightfoot Lee
William Williams
Matthew Thornton
John Morton
Thomas Lynch, Jr.

Team 2:
👑 Lewis Morris
Caesar Rodney
Thomas McKean
Thomas Heyward, Jr.
Benjamin Harrison
Charles Carroll of Carrollton
George Read
Button Gwinnett
Francis Lewis
Carter Braxton

Team 3:
👑 Robert Morris
Samuel Huntington
Robert Treat Paine
George Clymer
James Smith
Francis Hopkinson
George Wythe
Philip Livingston
Arthur Middleton
George Ross

Team 4:
👑 John Hart
Thomas Jefferson
William Paca
John Adams
John Penn
Thomas Stone
John Witherspoon
James Wilson
amin Franklin
George Walton

Team 5:
👑 Richard Stockton
Elbridge Gerry
William Hooper
William Floyd
George Taylor
Stephen Hopkins
Thomas Nelson, Jr.
William Ellery
William Whipple
Richard Henry Lee

Team 6:
👑 Samuel Adams
Edward Rutledge
John Hancock
Joseph Hewes
Josiah Bartlett
Roger Sherman
```

_Note: Apologies to the Declaration of Independence signatories for signifying team leadership with a crown! 🤣_
