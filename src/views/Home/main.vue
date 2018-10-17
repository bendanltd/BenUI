<template>
    <div class="main">
        <Layout>
            <div class="header">
                <Row>
                    <Col span="12"></Col>
                    <Col span="12"></Col>
                </Row>
            </div>
            <div class="site-content" style="width: 1140px;">
                <Layout>
                    <Content>Content</Content>
                    <Sider style="height:500px">Sider</Sider>
                </Layout>
            </div>
            <Footer style="background:red">Footer</Footer>
        </Layout>
    </div>
</template>

<script>
import "./main.less";
export default {};
</script>
