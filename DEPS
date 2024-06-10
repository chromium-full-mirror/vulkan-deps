# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'd2b2a3d0577def276ff2805934b32893ef3e9a01',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '27ebab7411bf59f9e9e42a5f6946a03eb9e425b8',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'eb49bb7b1136298b77945c52b4bbbc433f7885de',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c3178da8eac9bc7d1788e95f8d555918ba483c23',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd192041a2fc9c9fd8ae67d8ae3f32c5511541f04',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '03c0920555fc900b741f6eab0089cb6b52f9f506',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a9a1bcd709e185700847268eb4310f6484b027bc',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '07759f04791dc3fbb390174f0d24d4a792e0d357',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '35696789c7ec87ba49a4c338715ff860660510f0',
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
