<script>
import { faker } from '@faker-js/faker';
export const randomName = faker.name.findName(); 
export const randomEmail = faker.internet.email(); 
export const randomID = faker.helpers.createCard().phone; 
export const randomPicture = faker.internet.avatar();





</script>
<tr>
    <td>{randomID}</td>
    <td>{randomName}</td>
    <td>{randomEmail}</td>
    <td>
        <img src="{randomPicture}" alt="profilePicture"> 
    </td>
</tr>

<style>
td{
	border: 1px solid black;
    font-size: 20px;
}
</style>

