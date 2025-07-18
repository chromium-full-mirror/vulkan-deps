# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '15b727afdd0b69ef5d178727e7ac66be991e678f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '597e427cce3fc97a8455b26aba1a1189546717c3',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c8ad050fcb29e42a2f57d9f59e97488f465c436d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '257a227fbadf8176ea386c7d8fb9b889cbf08640',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '088a00d81d1fc30ff77aacf31485871aebec7cb2',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8f35302d38a547f60dc5f58ce042cc39e5874519',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '105d6c1fede00c3a9055e5a531ebf3d99bac406e',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'dc6f68172430999a96a209ef4700784917dab1a2',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2fbaf0ab0a0cb113e224ae81571c071a2f2be15c',
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
