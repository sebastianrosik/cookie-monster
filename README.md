# Cookie Monster
A javascript libary to manage cookies

## Installation

download [monster.js](https://github.com/jgallen23/cookie-monster/raw/master/dist/monster.js) from dist directory. 

or

	ender build cookie-monster 

## Usage

	monster.set(name, value, days, path, domain) //days, path and domain are optional
	monster.get(name)
	monster.remove(name)

## Example

	//set a cookie named 'cookiename' to '123' for 1 day then remove it
	var name = 'cookiename';
	var value = '123';
	var days = 1;
	monster.set(name, value, days);
	monster.remove(name);
