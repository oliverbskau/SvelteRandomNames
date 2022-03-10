<script>
import TableRow from "../TableRow/TableRow.svelte";
let peoples = [
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person",
    "person"
];
</script>
<table>
    <tr>
        <th>Id</th>
        <th>Name</th>
        <th>Email</th>
    </tr>
    {#each peoples as people}
 <TableRow people={people}/>
 {/each}
</table>

<style>
    table{
	width: 100%;
	margin: auto;
	border: 5px solid black
}
th{
	border: 1px solid black;
}
</style>
