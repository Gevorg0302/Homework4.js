<script>
const repeat = function(string, number)
const check = function(n) {
const line = function(str, n) {
if (n < 1) {
return;
}
if (n%2 === 0) {
console.log(str);
} else {
console.log(" " + str);
}
add(str, n - 1);
};
add(repeat(" * ", n), n);
};
</script>



<script>
function reverse(str)
{
if(str.length === 1) {
return str;
}
const sym = str[str.length - 1];
str = str.substring(0, str.length - 1);
return sym + reverse(str);
}
</script>
