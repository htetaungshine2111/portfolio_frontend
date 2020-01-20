<template>
  <el-table
    :data="users"
    border
    style="width: 90%; margin-top: 20px">
    <el-table-column
      prop="id"
      label="ID"
      width="180">
    </el-table-column>
    <el-table-column
      prop="name"
      label="Name"
      width="180">
    </el-table-column>
    <el-table-column
      prop="email"
      label="Email">
    </el-table-column>
    <el-table-column
      prop="created_at"
      label="Created At">
    </el-table-column>
  </el-table>
</template>

<script>
  import users from '~/apollo/queries/users'

  export default {
    apollo: {
      users: users
    }
  }


</script>
