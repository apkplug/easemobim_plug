# easemobim_plug
##环信IM组件
启动环信IM

    ComponentManager.getInstance().searchComponent(
        ComponentFactory.getInstance().getComponent("easemobimsdk"), 
        new ServerCallback<EaseMobIM>(){
            @Override
            public void onSuccess(EaseMobIM service) {
                //成功获取到了组件的服务
            }
            @Override
            public void onFailure(int errorNo, String strMsg)                       
            {
            }
        });
