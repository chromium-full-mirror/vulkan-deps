# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '43023b117abb3153e2ca400010d51dabebaae446',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '732b82663601cce1df89f294225be0569200ae38',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04f10f650d514df88b76d25e83db360142c7b174',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3ac12f1e37d20a6add31fa9a0f85720bdf1d4997',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3cfca3829608e778cf59b0dab55d77f4f6c79bee',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '075488ccd6600fea664e10ee2f946c76086827d2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '362c28b8e13292f0fca1b0c9ce3ba515fe9b71a1',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '906b27a77f4857fae6da3062df4cf6ab0c06e8d4',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7bdb79f243831ccf642309d0be69b53a533dff46',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
