<script>
import { faker } from '@faker-js/faker';
export const randomName = faker.name.findName(); 
export const randomEmail = faker.internet.email(); 
export const randomID = faker.helpers.createCard().phone; 
</script>
<tr>
    <td>{randomID}</td>
    <td>{randomName}</td>
    <td>{randomEmail}</td>
</tr>

<style>
td{
	border: 1px solid black;
}
</style>