function formatName (user){
return user.firstName+''+user.lastname;
}
const user={
first name:'Harper',
lastname:'perez'
};
const element=(
<h1>
hello,{formatName(user)};
</h1>
);
ReactDom.render(
element,
document.setelementById('root')
);
