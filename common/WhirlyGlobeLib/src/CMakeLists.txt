cmake_minimum_required(VERSION 3.4.1)

target_include_directories(
        ${WGTARGET}

        PUBLIC

        "${CMAKE_CURRENT_LIST_DIR}/../include/"
)

target_sources(
        ${WGTARGET}

        PUBLIC

        "${CMAKE_CURRENT_LIST_DIR}/../include/BaseInfo.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawable.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableBuilderGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableInstance.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableInstanceGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableInstanceBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BasicDrawableInstanceBuilderGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BillboardDrawableBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BillboardDrawableBuilderGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/BillboardManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ChangeRequest.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ComponentManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/CoordSystem.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Dictionary.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/DictionaryC.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Drawable.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/DrawableGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/DynamicTextureAtlas.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/DynamicTextureAtlasGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/FlatMath.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/FontTextureManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GeographicLib.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GeometryManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GeometryOBJReader.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GlobeAnimateHeight.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GlobeAnimateRotation.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GlobeAnimateViewMomentum.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GlobeMath.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GlobeView.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/GridClipper.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Identifiable.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ImageTile.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/IntersectionManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LabelManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LabelRenderer.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LayoutManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Lighting.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LinearTextBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LineAndPointShadersGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LoadedTileNew.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/LoftManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorFilter.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleBackground.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleCircle.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleFill.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleLayer.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleLine.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleRaster.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleSetC.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleSymbol.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorTileParser.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/VectorTilePBFParser.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MapboxVectorStyleSpritesImpl.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MaplyAnimateTranslateMomentum.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MaplyAnimateTranslation.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MaplyFlatView.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MaplyVectorStyleC.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MaplyView.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MarkerManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/MemManagerGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Moon.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/OverlapHelper.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ParticleSystemDrawable.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ParticleSystemDrawableGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ParticleSystemDrawableBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ParticleSystemDrawableBuilderGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ParticleSystemManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/PerformanceTimer.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Program.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ProgramGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Proj4CoordSystem.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadDisplayControllerNew.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadImageFrameLoader.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadLoaderReturn.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadSamplingController.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadSamplingParams.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadTileBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/QuadTreeNew.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/RawData.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/RawPNGImage.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/RenderTarget.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/RenderTargetGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Scene.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SceneGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SceneGraphManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SceneRenderer.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SceneRendererGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ScreenImportance.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ScreenObject.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ScreenSpaceBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ScreenSpaceDrawableBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ScreenSpaceDrawableBuilderGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SelectionManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ShapeDrawableBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ShapeManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/ShapeReader.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SphericalEarthChunkManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/SphericalMercator.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/StringIndexer.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Sun.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Tesselator.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/Texture.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/TextureGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/TextureAtlas.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/TriangleShadersGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/UtilsGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/vector_tile.pb.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/VectorData.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/VectorManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/VectorObject.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/VertexAttribute.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/VertexAttributeGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WhirlyGeometry.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WhirlyKitView.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WhirlyOctEncoding.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WhirlyVector.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WideVectorDrawableBuilder.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WideVectorDrawableBuilderGLES.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WideVectorManager.h"
        "${CMAKE_CURRENT_LIST_DIR}/../include/WrapperGLES.h"

        "${CMAKE_CURRENT_LIST_DIR}/BaseInfo.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawable.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableBuilderGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableInstance.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableInstanceGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableInstanceBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BasicDrawableInstanceBuilderGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BillboardDrawableBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BillboardDrawableBuilderGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/BillboardManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ChangeRequest.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ComponentManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/CoordSystem.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Dictionary.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/DictionaryC.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Drawable.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/DrawableGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/DynamicTextureAtlas.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/DynamicTextureAtlasGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/FlatMath.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/FontTextureManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GeographicLib.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GeometryManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GeometryOBJReader.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GlobeAnimateHeight.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GlobeAnimateRotation.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GlobeAnimateViewMomentum.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GlobeMath.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GlobeView.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/GridClipper.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Identifiable.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ImageTile.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/IntersectionManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LabelManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LabelRenderer.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LayoutManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Lighting.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LinearTextBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LineAndPointShadersGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LoadedTileNew.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/LoftManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorFilter.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleBackground.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleCircle.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleFill.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleLayer.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleLine.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleRaster.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleSetC.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleSymbol.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorTileParser.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/VectorTilePBFParser.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MapboxVectorStyleSpritesImpl.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MaplyAnimateTranslateMomentum.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MaplyAnimateTranslation.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MaplyFlatView.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MaplyVectorStyleC.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MaplyView.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MarkerManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/MemManagerGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Moon.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/OverlapHelper.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ParticleSystemDrawable.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ParticleSystemDrawableGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ParticleSystemDrawableBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ParticleSystemDrawableBuilderGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ParticleSystemManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/PerformanceTimer.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Program.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ProgramGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Proj4CoordSystem.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadDisplayControllerNew.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadImageFrameLoader.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadLoaderReturn.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadSamplingController.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadSamplingParams.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadTileBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/QuadTreeNew.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/RawData.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/RawPNGImage.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/RenderTarget.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/RenderTargetGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Scene.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SceneGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SceneGraphManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SceneRenderer.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SceneRendererGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ScreenImportance.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ScreenObject.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ScreenSpaceBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ScreenSpaceDrawableBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ScreenSpaceDrawableBuilderGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SelectionManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ShapeDrawableBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ShapeManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/ShapeReader.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SphericalEarthChunkManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/SphericalMercator.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/StringIndexer.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Sun.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Tesselator.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/Texture.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/TextureGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/TextureAtlas.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/TriangleShadersGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/UtilsGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/vector_tile.pb.c"
        "${CMAKE_CURRENT_LIST_DIR}/VectorData.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/VectorManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/VectorObject.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/VectorOffset.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/VertexAttribute.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/VertexAttributeGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WhirlyGeometry.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WhirlyKitView.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WhirlyOctEncoding.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WhirlyVector.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WideVectorDrawableBuilder.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WideVectorDrawableBuilderGLES.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WideVectorManager.cpp"
        "${CMAKE_CURRENT_LIST_DIR}/WrapperGLES.cpp"
)
