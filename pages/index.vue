<template>
  <h1>Hello!</h1>
</template>

<script>
import { PrismaClient } from '@prisma/client' 

const prisma = new PrismaClient({
  
})

export default {
  name: 'IndexPage'

}
</script>
