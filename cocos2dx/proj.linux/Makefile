TARGET = libcocos2d.so

INCLUDES += \
	-I../platform/third_party/linux/libfreetype2 \
	-I../platform/third_party/common/etc \
	-I../platform/third_party/common/s3tc \
        -I../platform/third_party/common/atitc \
	-I../../extensions \
	-I../../extensions/CCBReader \
	-I../../extensions/GUI/CCControlExtension \
	-I../../extensions/GUI/CCControlExtension \
	-I../../external/chipmunk/include/chipmunk \
	-I../../extensions/network \
        -I../../extensions/Components

SOURCES = ../actions/CCAction.cpp \
../actions/CCActionCamera.cpp \
../actions/CCActionEase.cpp \
../actions/CCActionGrid.cpp \
../actions/CCActionGrid3D.cpp \
../actions/CCActionInstant.cpp \
../actions/CCActionInterval.cpp \
../actions/CCActionManager.cpp \
../actions/CCActionPageTurn3D.cpp \
../actions/CCActionProgressTimer.cpp \
../actions/CCActionTiledGrid.cpp \
../actions/CCActionCatmullRom.cpp \
../actions/CCActionTween.cpp \
../base_nodes/CCAtlasNode.cpp \
../base_nodes/CCNode.cpp \
../cocoa/CCAffineTransform.cpp \
../cocoa/CCAutoreleasePool.cpp \
../cocoa/CCGeometry.cpp \
../cocoa/CCNS.cpp \
../cocoa/CCObject.cpp \
../cocoa/CCSet.cpp \
../cocoa/CCArray.cpp \
../cocoa/CCDictionary.cpp \
../cocoa/CCString.cpp \
../cocoa/CCDataVisitor.cpp \
../cocoa/CCData.cpp \
../event_dispatcher/CCAccelerationEvent.cpp \
../event_dispatcher/CCAccelerationEventListener.cpp \
../event_dispatcher/CCEvent.cpp \
../event_dispatcher/CCEventDispatcher.cpp \
../event_dispatcher/CCEventListener.cpp \
../event_dispatcher/CCKeyboardEvent.cpp \
../event_dispatcher/CCKeyboardEventListener.cpp \
../event_dispatcher/CCTouch.cpp \
../event_dispatcher/CCTouchEvent.cpp \
../event_dispatcher/CCTouchEventListener.cpp \
../event_dispatcher/CCCustomEvent.cpp \
../event_dispatcher/CCCustomEventListener.cpp \
../draw_nodes/CCDrawingPrimitives.cpp \
../draw_nodes/CCDrawNode.cpp \
../effects/CCGrabber.cpp \
../effects/CCGrid.cpp \
../label_nodes/CCFont.cpp \
../label_nodes/CCFontAtlas.cpp \
../label_nodes/CCFontAtlasCache.cpp \
../label_nodes/CCFontAtlasFactory.cpp \
../label_nodes/CCFontDefinition.cpp \
../label_nodes/CCFontFNT.cpp \
../label_nodes/CCFontFreeType.cpp \
../label_nodes/CCLabel.cpp \
../label_nodes/CCLabelAtlas.cpp \
../label_nodes/CCLabelBMFont.cpp \
../label_nodes/CCLabelTTF.cpp \
../label_nodes/CCLabelTextFormatter.cpp \
../label_nodes/CCTextImage.cpp \
../layers_scenes_transitions_nodes/CCLayer.cpp \
../layers_scenes_transitions_nodes/CCScene.cpp \
../layers_scenes_transitions_nodes/CCTransition.cpp \
../layers_scenes_transitions_nodes/CCTransitionPageTurn.cpp \
../layers_scenes_transitions_nodes/CCTransitionProgress.cpp \
../menu_nodes/CCMenu.cpp \
../menu_nodes/CCMenuItem.cpp \
../misc_nodes/CCMotionStreak.cpp \
../misc_nodes/CCProgressTimer.cpp \
../misc_nodes/CCClippingNode.cpp \
../misc_nodes/CCRenderTexture.cpp \
../particle_nodes/CCParticleExamples.cpp \
../particle_nodes/CCParticleSystem.cpp \
../particle_nodes/CCParticleSystemQuad.cpp \
../particle_nodes/CCParticleBatchNode.cpp \
../physics/Box2D/CCPhysicsContactInfo.cpp \
../physics/Box2D/CCPhysicsJointInfo.cpp \
../physics/Box2D/CCPhysicsShapeInfo.cpp \
../physics/Box2D/CCPhysicsBodyInfo.cpp \
../physics/Box2D/CCPhysicsWorldInfo.cpp \
../physics/chipmunk/CCPhysicsContactInfo.cpp \
../physics/chipmunk/CCPhysicsJointInfo.cpp \
../physics/chipmunk/CCPhysicsShapeInfo.cpp \
../physics/chipmunk/CCPhysicsBodyInfo.cpp \
../physics/chipmunk/CCPhysicsWorldInfo.cpp \
../physics/CCPhysicsBody.cpp \
../physics/CCPhysicsContact.cpp \
../physics/CCPhysicsShape.cpp \
../physics/CCPhysicsJoint.cpp \
../physics/CCPhysicsWorld.cpp \
../platform/CCSAXParser.cpp \
../platform/CCThread.cpp \
../platform/CCEGLViewProtocol.cpp \
../platform/CCFileUtils.cpp \
../platform/linux/CCStdC.cpp \
../platform/linux/CCFileUtilsLinux.cpp \
../platform/linux/CCCommon.cpp \
../platform/linux/CCApplication.cpp \
../platform/linux/CCEGLView.cpp \
../platform/linux/CCImage.cpp \
../platform/linux/CCDevice.cpp \
../platform/third_party/common/etc/etc1.cpp \
../platform/third_party/common/s3tc/s3tc.cpp \
../platform/third_party/common/atitc/atitc.cpp \
../script_support/CCScriptSupport.cpp \
../sprite_nodes/CCAnimation.cpp \
../sprite_nodes/CCAnimationCache.cpp \
../sprite_nodes/CCSprite.cpp \
../sprite_nodes/CCSpriteBatchNode.cpp \
../sprite_nodes/CCSpriteFrame.cpp \
../sprite_nodes/CCSpriteFrameCache.cpp \
../support/ccUTF8.cpp \
../support/CCProfiling.cpp \
../support/user_default/CCUserDefault.cpp \
../support/TransformUtils.cpp \
../support/base64.cpp \
../support/ccUtils.cpp \
../support/CCVertex.cpp \
../support/CCNotificationCenter.cpp \
../support/image_support/TGAlib.cpp \
../support/tinyxml2/tinyxml2.cpp \
../support/zip_support/ZipUtils.cpp \
../support/zip_support/ioapi.cpp \
../support/zip_support/unzip.cpp \
../support/data_support/ccCArray.cpp \
../support/component/CCComponent.cpp \
../support/component/CCComponentContainer.cpp \
../text_input_node/CCIMEDispatcher.cpp \
../text_input_node/CCTextFieldTTF.cpp \
../textures/CCTexture2D.cpp \
../textures/CCTextureAtlas.cpp \
../textures/CCTextureCache.cpp \
../tilemap_parallax_nodes/CCParallaxNode.cpp \
../tilemap_parallax_nodes/CCTMXLayer.cpp \
../tilemap_parallax_nodes/CCTMXObjectGroup.cpp \
../tilemap_parallax_nodes/CCTMXTiledMap.cpp \
../tilemap_parallax_nodes/CCTMXXMLParser.cpp \
../tilemap_parallax_nodes/CCTileMapAtlas.cpp \
../shaders/CCGLProgram.cpp \
../shaders/ccGLStateCache.cpp \
../shaders/CCShaderCache.cpp \
../shaders/ccShaders.cpp \
../kazmath/src/aabb.c \
../kazmath/src/plane.c \
../kazmath/src/vec2.c \
../kazmath/src/mat3.c \
../kazmath/src/quaternion.c \
../kazmath/src/vec3.c \
../kazmath/src/mat4.c \
../kazmath/src/ray2.c \
../kazmath/src/vec4.c \
../kazmath/src/neon_matrix_impl.c \
../kazmath/src/utility.c \
../kazmath/src/GL/mat4stack.c \
../kazmath/src/GL/matrix.c \
../CCCamera.cpp \
../CCConfiguration.cpp \
../CCDirector.cpp \
../CCScheduler.cpp \
../ccFPSImages.c \
../ccTypes.cpp \
../cocos2d.cpp \
../CCDeprecated.cpp

COCOS_ROOT = ../..

include cocos2dx.mk

CXXFLAGS += -Wno-sequence-point
CCFLAGS += -Wno-sequence-point

STATICLIBS += $(LIB_DIR)/libchipmunk.a

TARGET := $(LIB_DIR)/$(TARGET)

all: $(TARGET)

$(TARGET): $(OBJECTS) $(CORE_MAKEFILE_LIST)
	@mkdir -p $(@D)
	$(LOG_LINK)$(CXX) $(CXXFLAGS) $(OBJECTS) -shared -o $@ $(SHAREDLIBS) $(STATICLIBS) $(LIBS)

$(OBJ_DIR)/%.o: ../%.cpp $(CORE_MAKEFILE_LIST)
	@mkdir -p $(@D)
	$(LOG_CXX)$(CXX) $(CXXFLAGS) $(INCLUDES) $(DEFINES) -c $< -o $@

$(OBJ_DIR)/%.o: ../%.c $(CORE_MAKEFILE_LIST)
	@mkdir -p $(@D)
	$(LOG_CC)$(CC) $(CCFLAGS) $(INCLUDES) $(DEFINES) -c $< -o $@
