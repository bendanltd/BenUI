<template>
    <div class="main">
        <div class="header">
            <Row class="site-center main-maxwidth">
                <Col :xs="24" :sm="18" :md="18" :lg="18">
                <div style="float:left">
                  <div>BenUI</div>
                <div>你好</div>
                </div>
                </Col>
                <Col :xs="0" :sm="6" :md="6" :lg="6">
                <div style="float:right;">
                     <Button type="info" ghost size="small">登录</Button>
                     <Button type="warning" ghost style="margin-left:2px;" size="small">注册</Button>
                </div>
                </Col>
            </Row>
        </div>
        <div class="main-context">
            <div class="site-center main-maxwidth">
                <Row class="site-center main-maxwidth">
                    <Col :xs="24" :sm="18" :md="18" :lg="18">
                    <div class="content">
                        aaaaa
                    </div>
                    </Col>
                    <Col :xs="0" :sm="6" :md="6" :lg="6">
                    <div class="sider">
                        aaaaa
                    </div>
                    </Col>
                </Row>
            </div>
        </div>
       <div class="footer">
        </div>
    </div>
</template>

<script>
import "./main.less";
export default {};
</script>
