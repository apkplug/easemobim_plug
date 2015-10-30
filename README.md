# easemobim_plug
##环信IM组件
启动环信IM

ComponentManager.getInstance().searchComponent(
    ComponentFactory.getInstance().getComponent("组件名称"), 
    new ServerCallback<组件接口类型>(){
        @Override
        public void onSuccess(组件接口类型 service) {
            //成功获取到了组件的服务
        }
        @Override
        public void onFailure(int errorNo, String strMsg)                       
        {
        }
    });
